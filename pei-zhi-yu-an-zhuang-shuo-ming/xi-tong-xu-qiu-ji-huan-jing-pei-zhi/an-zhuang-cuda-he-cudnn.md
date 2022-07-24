# 安装CUDA和cuDNN

## CUDA安装

paddlepaddle安装需要依赖CUDA环境.，本次开发的环境是CUDA10.2。 如果您使用的是安培架构的GPU（NVIDIA GeForce 30系列），推荐使用CUDA11以上，非安培架构CPU推荐使用CUDA10.2。 CUDA各版本下载地址：

{% embed url="https://developer.nvidia.com/cuda-toolkit-archive" %}

下载完成后依照默认安装程序逐步执行即可。

{% hint style="info" %}
paddlepaddle目前支持快速安装的CUDA版本为10.1—11.2，其他版本需自行下载源码编译。
{% endhint %}

## cuDNN安装

下载地址：

{% embed url="https://developer.nvidia.com/rdp/cudnn-download" %}

登录或注册账号后，下载与CUDA相对应版本的cuDNN，得到⼀个压缩包，将压缩包中的bin，include，lib目录下的文件复制到CUDA安装目录下的同名文件夹内。

{% hint style="info" %}
您必须拥有一个NVIDIA开发者账户才可下载cuDNN，cuDNN是PaddlePaddle运行的必须依赖。
{% endhint %}

## 验证安装

控制台执行 `nvcc -V` 显示版本号则安装成功。

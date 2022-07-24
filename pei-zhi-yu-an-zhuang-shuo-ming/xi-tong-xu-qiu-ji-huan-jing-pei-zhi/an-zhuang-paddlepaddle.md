# 安装PaddlePaddle

确认Python版本

```bash
python --version
```

确认pip版本是否为20.2.2或更高版本：

```bash
python -m pip --version
```

如果pip版本不符合要求，使⽤如下命令更新:

```bash
python -m pip install --upgrade pip
```

CUDA安装成功后，根据安装的CUDA版本，执行对应的安装指令（以CUDA 10.2为例）：

```bash
python -m pip install paddlepaddle-gpu==2.3.0 -i https://mirror.baidu.com/pypi/simple
```

其他版本的安装说明详见PaddlePaddle官网：

{% embed url="https://www.paddlepaddle.org.cn/install/quick?docurl=/documentation/docs/zh/install/pip/windows-pip.html" %}

完成安装后，进入Python命令行，使用以下命令进行检查安装是否正确：

```python
import paddle
 paddle.utils.run_check()
```

如果出现 `PaddlePaddle is installed successfully!`说明您已安装成功。

{% hint style="info" %}
您可以使用Anaconda等管理工具来建立一个全新的虚拟环境，这将会使环境的冲突可能性降到最低。
{% endhint %}

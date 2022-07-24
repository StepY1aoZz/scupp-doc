# 安装PaddleRS

PaddleRS是基于飞桨框架开发的高性能遥感图像处理开发套件，能够端到端地完成从训练到部署的全流程遥感深度学习应用。我们的系统基于PaddleRS开发，故需要您提前安装好PaddleRS。

{% hint style="info" %}
PaddleRS安装的前置要求为PaddlePaddle>=2.2.0，请提前确认您的PaddlePaddle版本是否符合要求。
{% endhint %}



* PaddleRS安装

PaddleRS代码会跟随开发进度不断更新，可以安装develop分支的代码使用最新的功能，安装方式如下：

```
git clone https://github.com/PaddleCV-SIG/PaddleRS
cd PaddleRS
git checkout develop
pip install -r requirements.txt
python setup.py install
```

{% hint style="warning" %}
请注意，由于PaddleRS仍然处于不稳定的版本迭代中，故直接使用最新版可能会导致本系统的错误。
{% endhint %}



* GDAL安装

PaddleRS支持多种类型的卫星数据IO以及地理处理等，需要使用GDAL，安装方式如下：

{% tabs %}
{% tab title="Linux/MacOS" %}
推荐使用conda进行安装（需要您提前安装好Anaconda/MIniconda等环境）

```
conda install gdal
```
{% endtab %}

{% tab title="Windows" %}
Windows用户可以通过[这里](https://www.lfd.uci.edu/\~gohlke/pythonlibs/#gdal)下载对应Python和系统版本的二进制文件（\*.whl）到本地，以_GDAL‑3.3.3‑cp39‑cp39‑win\_amd64.whl_为例，进入下载目录进行安装:

```
cd download
pip install GDAL‑3.3.3‑cp39‑cp39‑win_amd64.whl
```
{% endtab %}
{% endtabs %}

# LongeOS Video 视频播放器

使用Qt/QML和libmpv构建的开源视频播放器。

### 第三方代码

[haruna](https://github.com/g-fb/haruna)

## 依赖包

```shell
sudo apt install extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev libmpv-dev
```

# 构建和安装

```
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

# License

This project has been licensed by GPLv3.

# iOS快速集成指南

### 下载sdk

---

### 导入sdk以及工程设置

---

1. 拷贝MXKit.framework、MXKitResources.bundle和MXKit\_Version.txt到相应得工程目录下，并且添加到工程里

2. 在工程文件的Build Phases 里面添加用到的Libraries:![](/assets/buildparse1.png)![](/assets/buildparse2.png)

3. 在target的build setting里面添加 -ObjC和-lresolv  ![](/assets/linkFlag.png)

# 编码实现

---




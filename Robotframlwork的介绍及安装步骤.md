# 1.RF介绍及环境搭建

## 步骤

1. 下载python3.0
2. python3.0环境变量配置
3. 安装Robotframework

```shell
pip install robotframework
pip install robotframework-ride
```

## 总结

### 1. 装ride时报超时的错

```shell
# 先设置超时时间为1000
pip install robotframework-ride --default-timeout=1000
# 如果还是报超时的错，则换源处理
pip install robotframework-ride --default-timeout=1000 -i https://pypi.tuna.tsinghua.edu.cn/simple
```

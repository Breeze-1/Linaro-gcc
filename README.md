# 交叉编译工具链

##  本 REPO 从 Linaro 下载了 gcc 11，12，13 版本的 aarch64 与 arm 的交叉编译工具链

### 使用方法

```bash
tar -zxvf #解压命令
#然后移动到 /opt 目录下
```

# 设置环境变量(LINUX)

```bash
# 临时生效，在当前终端执行:export PATH=$PATH:/opt/<你所下载的gcc工具链>/bin
# 只对当前用户生效: vim .bashrc ,然后在最后添加:export PATH=$PATH:/opt/<你所下载的gcc工具链>/bin
#然后执行: source .bashrc
#对所有用户生效: sudo vim /etc/profile
#在最后一行加上:export PATH=$PATH:/opt/<你所下载的gcc工具链>/bin
#后 source /etc/profile
```

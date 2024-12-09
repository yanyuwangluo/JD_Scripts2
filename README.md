# 电信脚本

###使用方法
```
// 变量
#电信
export chinaTelecomAccount="phone#服务密码"

#高版本青龙添加这一行,低版本忽略。
export NODE_OPTIONS="${NODE_OPTIONS} --tls-cipher-list=DEFAULT@SECLEVEL=0"

#电信兑话费
export jdhf="phone@服务密码&phone2@服务密码"

// 依赖
//删除原来的 httpx
httpx==0.16.1
PyExecJS
pycryptodome
//别的自己缺什么自己装。

//依赖源
//Node 软件包镜像源
https://registry.npmmirror.com
//Python 软件包镜像源
https://mirrors.aliyun.com/pypi/simple/
//Linux 软件包镜像源
https://mirrors.aliyun.com
```

###脚本不是我写的，有什么问题也不要找我，来源网络搬运。
# sspchecknode
一直以来sspanel v3通过数据库连接到前端有个问题，后端节点经常由于网络问题联络不到前端于是就会停止发送呼吸包，而网络恢复了之后一定几率后端不会主动嗅探重新发送呼吸包，但是其实python后端还在运行，也就是节点其实可以正常连接，但是前端会报节点是连。

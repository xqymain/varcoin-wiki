#varcoind
varcoind是varcoin加密货币的守护进程，负责同步和运行网络，是最基础最重要的部分。
##启动过程
初次启动，varcoind会在用户目录下生成`.varcoin`目录，负责存储区块链文件和基础配置。
经过初始化和同步区块链的过程，varcoind就启动成功了。
##操作指令
你可以在varcoind下输入命令以对当前网络信息进行查看和对本机的状态进行调整。
主要包括：
  print_pl (pp) 输出当前运行网络用户的列表
  print_cn (pc) 输出其他节点与本节点的链接
  print_bc (pb) 输出给定范围内区块的区块链信息 print_bc | pb <开始区块>　[<结束区块>]
  print_block (pbk) 输出给定区块信息 print_block | pbk <块哈希> | <块高度>
  print_tx (ptx) 输出给定的转账信息  print_tx | ptx <转账哈希>
  start_mining (sm) 开始挖矿操作     start_mining | sm <钱包地址>
  stop_mining (spm) 停止挖矿操作     stop_mining | spm
  print_pool    输出转账池(长格式)
　print_pool_sh 输出转账池(短格式)
  show_hr (shr) 显示挖矿算力
  hide_hr (hhr) 隐藏挖矿算力
  save          保存区块链
  set_log       设置日志级别 0-4

只有当执行save或exit时才会保存区块链文件，请悉知！

Enjoy :)

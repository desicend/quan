# quan

我的 Quantumult X（圈X）自用规则仓库。

## 目录
- `weibo.conf`：微博 / 微博国际版净化重写（来源见文件头部注释）。
- `emby_direct.list`：自用 Emby 分流规则（示例，需按你的策略名调整）。

## 远程引用（Raw 链接）
把下面链接粘到 Quantumult X 的对应 remote 引用里即可：
- Emby 分流：`https://raw.githubusercontent.com/desicend/quan/main/emby_direct.list`
- 微博净化：`https://raw.githubusercontent.com/desicend/quan/main/weibo.conf`

## 规则写法速记
- `DOMAIN-SUFFIX,example.com,Policy`：匹配所有以 example.com 结尾的域名（含子域名）。
- 分流规则一般是：`TYPE,VALUE,POLICY`（一行一条）。

> 提醒：你原来的 `eycc.list` / `eycc.ymal` 里规则缺少策略名，会导致 Quantumult X 无法按预期分流。

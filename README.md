# jkb-simulator

基于 Web 的北京健康宝模拟。

**不要核酸要吃饭  不要封控要自由  不要谎言要尊严**

**不要文革要改革  不要领袖要选票  不做奴才做公民**

## 使用说明

- 点击姓名、证件号可以修改相应信息
- 点击照片可以更改或移除照片，超过 4MB 的图片可能无法在本地保存
- 点击右上角二维码标志可以在 “本人健康码自查询” 和 “本人信息扫码登记” 间切换
- 点击 “未见异常” 可以切换 “通勤” 标志
- 可以作为 PWA (Progressive Web Apps) 添加到主屏幕上
  - 在 Safari (iOS) 上，点击下方“分享”按钮，再点击“添加至主屏幕”
  - 在 Chrome (Android) 上，点击右上角菜单按钮，再点击“添加至主屏幕”
  - 在 Firefox (Android) 上，点击右上角菜单按钮，再点击“安装”

## 网页 Demo

Cloudflare: [jkb.pages.dev](https://jkb.pages.dev)

Netlify: [gleeful-strudel-e8ba91.netlify.app](https://gleeful-strudel-e8ba91.netlify.app)

使用 Demo 时请注意：我们不会主动收集任何访问数据，但不保证网站托管的服务商不会收集访问信息。若担心隐私，可以从 [GitHub Releases](https://github.com/ilovexjp/jkb-simulator/releases) 中下载源码自行部署。

## 附言

GitHub 曾以违反 TOS（服务条款）为由删除我们的仓库及 GitHub Pages，所以目前源码只放在 Releases 中。另请关注 Telegram 频道 [@gh_ilovexjp](https://t.me/gh_ilovexjp) ，以免账号被封禁后无法获取到更新。

这个项目的源码不含与除部署网页的服务器外其它服务器的交流，所有信息的更改保存在本地 `localStorage` 中，仅当前域可访问。更改信息时，清空输入框并确认可以恢复该项默认值；清除浏览器的浏览数据会恢复所有项的默认值。

本项目**不保证**与官方页面同步更新，亦**不可用于**查验。

如有**针对本项目**的 Bug Report 与 Feature Request 等，可在 Issues 中提出；无关这一项目的议题将可能被删除。

如果你想与我们共同工作，可以发邮件至 ilovexjp@protonmail.com。请注意保护个人信息安全。

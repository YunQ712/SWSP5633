SWSP5633 静态网站文件

index.html：网站主页，包含四个 Module；Module 03 已加入四个可独立点击展开的子模块。
jack.html：Jack 的互动情景页面，由主页的 Jack 情景卡片打开；情境介绍页使用 Setting、Your role、About Jack 卡片布局。
alex.html：Alex 的 NDIS Assessment 互动情景页面，由主页的 Alex 情景卡片打开；包含情境介绍页。
marko.html：Marko 的 Youth Care Planning 三阶段互动情景页面；包含情境介绍页。
所有 simulation 页面顶部统一显示 Interactive Simulations 与 Initial Engagement，Back to home page 和 Restart Simulation 按钮靠右；颜色与首页一致。Jack 每个 Continue 前有 Back，Alex 和 Marko 的第一步 Back 可返回情境介绍。Simulation 页面不重复显示 Acknowledgement of Country。首页底部以 References 作为页脚标题，引用列表显示在标题下方，无展开按钮且不编号。

jack-data.json：Jack 情景的可编辑数据副本。jack.html 使用自身内嵌的数据；单独修改此 JSON 不会改变网页内容。

部署到 GitHub/Vercel 时，请将 index.html、jack.html、alex.html 和 marko.html 放在同一目录，并保留文件名。若只部署网页，jack-data.json 可以不上传；建议保留它以便后续维护情景内容。

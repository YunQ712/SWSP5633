SWSP5633 静态网站文件

index.html：网站主页，包含四个 Module；Module 03 已加入四个可独立点击展开的子模块。
jack.html：Jack 的互动情景页面，由主页的 Jack 情景卡片打开。
alex.html：Alex 的 NDIS Assessment 互动情景页面，由主页的 Alex 情景卡片打开。
marko.html：Marko 的 Youth Care Planning 三阶段互动情景页面。
jack-data.json：Jack 情景的可编辑数据副本。jack.html 使用自身内嵌的数据；单独修改此 JSON 不会改变网页内容。

部署到 GitHub/Vercel 时，请将 index.html、jack.html、alex.html 和 marko.html 放在同一目录，并保留文件名。若只部署网页，jack-data.json 可以不上传；建议保留它以便后续维护情景内容。

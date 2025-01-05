# mdbook 电子书模板


## 使用方法

1. clone 本仓库
2. 移除 .git 文件夹
3. 重新初始化 .git
4. 修改 book.toml 中的配置信息
5. 修改 [theme/index.hbs](theme/index.hbs#L203) 中的备案号（Optional）
5. 配置 CI 部署（ Zeabur 直接使用 gh-pages 部署即可）

## 本地渲染说明

1. 安装 `cargo install mdbook mdbook-linkcheck`
2. 执行 `mdbook serve` 即可
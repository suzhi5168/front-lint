# feng-markdownlint-config

> 文档规范

支持配套的 [markdownlint 可共享配置](https://www.npmjs.com/package/markdownlint#optionsconfig)。

## 安装

需要先行安装 [markdownlint](https://www.npmjs.com/package/markdownlint)：

```bash
pnpm add -D markdownlint feng-markdownlint-config
```

## 使用

在 `.markdownlint.json` 中继承本包:

```json
{
	"extends": "encode-fe-markdownlint-config"
}
```

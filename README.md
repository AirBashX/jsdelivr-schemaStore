# jsdelivr-schemaStore

SchemaStore加速镜像

镜像地址:https://fastly.jsdelivr.net/gh/AirBashX/jsdelivr-schemaStore@main/catalog.json

![GitHub Repo stars](https://github.com/AirBashX/jsdelivr-schemaStore)
[![](https://data.jsdelivr.com/v1/package/gh/AirBashX/jsdelivr-schemaStore/badge)](https://www.jsdelivr.com/package/gh/AirBashX/jsdelivr-schemaStore)
## 功能
将SchemaStore中catalog.json文件中的github地址替换为jsdelivr链接,从而实现加速

每24小时更新一次

## 使用

### Sublime
[LSP-yaml](https://packagecontrol.io/packages/LSP-yaml)
```json
"yaml.schemaStore.url": "https://fastly.jsdelivr.net/gh/AirBashX/jsdelivr-schemaStore@main/catalog.json"
```

### Vscode
[redhat.vscode-yaml](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
```json
"yaml.schemaStore.url": "https://fastly.jsdelivr.net/gh/AirBashX/jsdelivr-schemaStore@main/catalog.json"
```
> _包括但不限于以上编辑器和拓展,凡是支持修改schemaSToreURl的编辑器和拓展均支持_

---
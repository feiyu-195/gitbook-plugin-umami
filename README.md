# gitbook-plugin-umami
使用 **NPM** 安装插件:
```shell
$ npm install gitbook-plugin-umami
```
在 book.json 中使用插件:
```shell
{
    "plugins": ["umami"]
}
```
在 book.json 中添加配置，设置umami的站点url和date-website-id:
```shell
{
    "plugins": ["umami"],
    "pluginsConfig": {
        "umami": {
            "url": "http(s)://xxxx/random-string.js"
            "website-id": "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
        }
    }
}
```

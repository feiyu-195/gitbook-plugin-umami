# gitbook-plugin-umami
使用 NPM 安装插件:

$ npm install gitbook-plugin-umami
在 book.json 中使用插件:

{
    "plugins": ["umami"]
}
在 book.json 中添加配置，设置umami网站中的url和date-website-id:

{
    "plugins": ["umami"],
    "pluginsConfig": {
        "umami": {
            "url": "http(s)://xxx/random-string.js"
            "website-id": "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
        }
    }
}

# 陈阳小草Iss服务器列表

使用 [A2S] 构建的服务器信息查询。  
使用[sourcequery]修改而来

## 本地运行

运行 `python3 querysite.py` 用浏览器打开 [http://localhost:8090](http://localhost:8090)

## 部署

关于flask部署 [Deployment Options]. 这里放了一个gunicorn的示例文件 `gunicorn.conf`.

## 部署方式

* [python-a2s]
* [flask]

## License

AGPLv3

[sourcequery]:https://github.com/Yepoleb/sourcequery
[A2S]: https://developer.valvesoftware.com/wiki/Server_queries
[python-a2s]: https://github.com/Yepoleb/python-a2s
[flask]: http://flask.pocoo.org/
[Deployment Options]: http://flask.pocoo.org/docs/latest/deploying/

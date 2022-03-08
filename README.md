# It's full of bug 持续记录中...
* maven nexus搭建私服后，构建时不会下载最新代码(确认已deploy) <br/>  
> 经大哥帮助得知因为使用版本号构建时不会下载新文件，需采用快照(SNAPSHOT),版本号不变，且后缀必须带上-SNAPSHOT 真是问题虽简单，不了解坑死人


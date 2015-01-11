##前言##
当前0.5版，基本我想要实现的功能都实现了，请多给意见
渣代码，所以就不太想往那些分享workflow的网站去了

网易云音乐Mac客户端目前应该还没有啥接口，没法方便的调用。因此最终归宿都是打开浏览器。



##快捷键和功能介绍：##

- wy 就是网易的意思，s=song，a=album，art=artist，p=playlist

- 根据歌曲名字搜索：```wys 歌曲名```

![wys]

- 根据专辑名字搜索：```wya 专辑名```  
  - 搜到想要的专辑后，按回车会进入该专辑曲目列表。也即自动执行 ```wyaid 专辑编号```

![wya]![wyaid]

- 根据歌手名字搜索：```wyart 歌手名```
  - 搜到想要的歌手后，按回车会进入该歌手专辑列表。也即自动执行 ``` wyartid 歌手编号```
  - 对某个专辑继续按回车，就会进入该专辑曲目列表。也即自动执行 ```wyaid 专辑编号```

![wyart]![wyartid]

- 根据歌单名字搜索：```wyp 歌单名```
  - 搜到想要的歌单后，按回车会进入该歌单曲目列表。也即自动执行 ``` wypid 歌手编号```

![wyp]![wypid]

- 由于搜索时会下载各种封面图片，所以记得运行缓存清理（虽然图都很小）```wyclean```

- 由于上述不少执行命令是相互调用的，因此尽量避免修改命令的运行触发关键词（尤其是带wyaid wyartid wypid这种带id的）

  

[wys]: intro/wys.png
[wya]: intro/wya.png
[wyaid]: intro/wyaid.png
[wyart]: intro/wyart.png
[wyartid]: intro/wyartid.png
[wyp]: intro/wyp.png
[wypid]: intro/wypid.png


##下载##

[Alfred插件下载](https://github.com/goodbest/Alfred_Workflow_Music163/blob/master/Music163_alfred_workflow_v0.5.alfredworkflow?raw=true)

[Github Repo](https://github.com/goodbest/Alfred_Workflow_Music163)


## Licensing, thanks ##

This workflow uses the [Alfred-Workflow](http://www.deanishe.net/alfred-workflow/) library and some code from [yanunon](https://github.com/yanunon/NeteaseCloudMusic)

# [Vtb-Music](https://santiego.gitee.io/vtb-music/)

[https://santiego.gitee.io/vtb-music/](https://santiego.gitee.io/vtb-music/)

**一个收录VTuber歌曲的音乐网站🎧**

得利于Gitee，各位有能DD都可以参与贡献开发！

如何上传歌曲？如何新建人物？[参考这里！](https://gitee.com/santiego/vtb-music/wikis/%E5%A6%82%E4%BD%95%E4%B8%8A%E4%BC%A0%E6%AD%8C%E6%9B%B2?sort_id=2062741)

官方交流QQ大群： `737972812`，欢迎各位`dd`加入讨论、上传歌曲

开发小组QQ群：`392381367`，欢迎开发大佬加入

[网站指南Wiki](https://gitee.com/santiego/vtb-music/wikis/Vtb-Music)

---

记得大概3月下旬左右，当时听完星姐的歌回LIVE后，热泪盈眶，一时冲动花了几个中午写了一个网站，利用gitee的`pages`服务，并让用户通过提交`pull request`的方式来上传歌曲。

之后，越来越多的dd无偿参与到网站的建设，歌曲从原来建站时的两位数猛增到现在的500+；

越来越多的开发大佬加入到我们，如今网站已经开始脱离gitee，开始拥有了自己的服务器和后端（网页仍部署在gitee上）……

但是网站仍然需要更多的开发者参与，网站现在需要**开发App**，需要**重构老旧完全原生的前端**

如果你也是一位有能dd，有意愿请加入我们，一起开发、完善这个网站，请联系我们：

vtb-music官方QQ大群：`737972812`

vtb-music开发者小组QQ群：`392381367`

（打轴\翻译\剪辑man也可以来哦~）

<<<<<<< HEAD

=======
>>>>>>> 5e950395e99098a7db939bc2f4becacdfc3e53b0
---

## 开发

#### 总

目前网站暂时依托于`Gitee Pages`服务，已拥有网站自己的服务器和后端，后端上传歌曲功能即将上线(之前是通过用户提交`pull request`来上传歌曲的)

**网站后端（[项目地址](https://gitee.com/Dishone/vtb-music-admin-netcore)）正在由[Dishone](https://gitee.com/Dishone)开发中**，即将上线。

**网站前端**（适配后端api）：[vtb-music-web](https://gitee.com/mrams/vtb-music-web) **（在这个仓库进行最新开发）**

#### 关于前端

网站前端没有使用任何框架，全部由原生`jQuery`开发，虽然是静态网页，但由数据驱动、动态渲染。另外如你所见，**Vtb-Music**基于Gitee Pages 服务，所有网页、歌曲、数据均保存在Gitee仓库中，也正因如此，直接省去了网站后端，也使各位有能DD可以**直接参与**到**Vtb-Music**的开发维护（决定因素还是因为不用租服务器🤣）。但有利有弊，由于Gitee Pages 服务的限制，后端全部由前端完成渲染，并且用户部分交互需要通过Gitee完成，较为繁琐。

目前需要有能man使用框架重构前端代码（比如`vue.js`）

本站是完全开源开放且部署在[gitee](https://gitee.com/)上的，所以各位dd可以通过gitee上传歌曲甚至参与开发，**欢迎各位有能DD参与开发**。
因为开发者本人为在校高中生，所以`pull request`审核可能稍慢，网站代码质量、可读性望包涵。

下一步开发目标：

- [x] 适配手机端
- [x] 音量控制
- [x] 添加艺人官方账号链接
- [x] 播放器UI改进
- [x] 滚动字幕
- [ ] 考虑使用`vue.js`重构

#### 相关项目仓库地址

- 网站后端 [vtb-music-admin-netcore](https://gitee.com/Dishone/vtb-music-admin-netcore)
- 网站新前端 [vtb-music-web](https://gitee.com/mrams/vtb-music-web)

- 网站数据仓库 [data-4](https://gitee.com/santiego/vtb-music-source-data-4)
- 网站数据仓库 [data-3](https://gitee.com/santiego/vtb-music-source-data-3)（已无法访问）
- 网站数据仓库 [data-2](https://gitee.com/santiego/vtb-music-source-data-2)
- 网站数据仓库 [data-1-song](https://gitee.com/santiego/vtb-music-source-song) [data-1-img](https://gitee.com/santiego/vtb-music-source-img) [data-1-lyric](https://gitee.com/santiego/vtb-music-source-lyric)
- 网站图床 [vtb-music-source-img](https://gitee.com/santiego/vtb-music-source-img)

## [声明](https://gitee.com/santiego/vtb-music/wikis/%E5%A3%B0%E6%98%8E)



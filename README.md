# 教你如何用 PPT 制作炫酷抖动的雪球君

>  ⚠️请使用 CC98 网页版浏览本帖，小程序无法正常渲染本帖

前两天刚刚给 [NexusHD](http://www.nexushd.org/) 更换了一个头图，效果如下：

![img](http://file.cc98.org/v2-upload/bixvvivq.gif)

同时也收获了部分好评：

![image-20210706230305481](http://file.cc98.org/v2-upload/dq5tttic.png)

甚至有用户把它用在了 98 签名档：[@北斗青榷](https://www.cc98.org/user/id/559130)

授人以鱼不如授人以渔，本篇文章我准备以 CC98 的[雪球君](https://www.cc98.org/topic/4975118)为例，给大家介绍一下这个动图的制作方法。

![抖动的雪球君](http://file.cc98.org/v2-upload/vfxkbyqa.gif)

相信看完后你也能够收获一只（一对？）抖动的雪球君![img](https://www.cc98.org/static/images/98LOGO.ico)👈找到我了吗？

## 🛠️准备工作

制作过程需要用到的工具有：

- [Microsoft PowerPoint](https://www.microsoft.com/zh-cn/microsoft-365/powerpoint)

  可以去浙大[校园正版化软件平台](http://ms.zju.edu.cn/microsoft/download.html)获取正版，PPT 是制作这个效果的主要工具；

- [BrightSlide PPT 插件](https://www.brightcarbon.com/brightslide/)

  该插件支持 [Windows](https://www.brightcarbon.com/brightslide/?os=windows) 与 [MacOS](https://www.brightcarbon.com/brightslide/?os=mac) 系统，这里用到了它的[添加动作路径](https://www.brightcarbon.com/brightslide/help/#:~:text=Paste%20as%20Motion%20Path)和[动画格式刷](https://www.brightcarbon.com/brightslide/help/#:~:text=Animation%20Painter)功能；

- [ScreenToGif](https://www.screentogif.com/)*

  可选安装，用来将视频转换成 gif 动图。也可选用其它能够完成此任务的工具，比如 [FFmpeg](http://ffmpeg.org/) 等；

- [Adobe Photoshop](https://www.adobe.com/cn/products/photoshop.html)* 和 [Adobe Illustrator](https://www.adobe.com/cn/products/illustrator.html)*

  可选安装，同样可以去浙大[校园正版化软件平台](http://ms.zju.edu.cn/microsoft/download.html)获取正版，主要用于图像处理。本次主角雪球君只用 PPT 所提供的功能即可，也可选用其它顺手的图片编辑工具。

## 📝制作步骤

1. 首先当然是找到一张雪球君分辨率较高的图片

   经常水 98 的小伙伴肯定可以发现，[@CC98赞助](https://www.cc98.org/user/id/558500)这个账户的头像就是雪球君，而且图片足够清晰，把它保存到本地即可：

   |                         1.a 获取方式                         |                      1.b 原图                       |
   | :----------------------------------------------------------: | :-------------------------------------------------: |
   | [![image-20210706233633202](http://file.cc98.org/v2-upload/ib3f5dbc.png)](https://www.cc98.org/user/id/558500) | ![img](http://file.cc98.org/v2-upload/x4xe1vqq.png) |

2. 接下来新建一个空白演示文稿，并将版式改为空白：

   |                     2.a 新建空白演示文稿                     |                      2.b 将版式改为空白                      |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210706235323956](http://file.cc98.org/v2-upload/kubruypf.png) | ![image-20210707000651161](http://file.cc98.org/v2-upload/yakn4uqy.png) |

3. 将幻灯片大小改为正方形，并将背景色设置为深灰色：

   |                  3.a 更改幻灯片大小为正方形                  |                    3.b 将背景色设为深灰色                    |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707000921477](http://file.cc98.org/v2-upload/ozrkicl4.png) | ![image-20210707000522760](http://file.cc98.org/v2-upload/l0ftbctf.png) |

4. 把雪球君图片粘贴过来并将白色部分设置为透明色，然后调整到合适大小放置在页面中央：

   |                        4.a 设置透明色                        |                      4.b 调整大小和位置                      |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707021426075](http://file.cc98.org/v2-upload/dqagov2m.png) | ![image-20210707001420225](http://file.cc98.org/v2-upload/ixkj5snc.png) |

5. 设置图片格式，利用内部阴影效果将雪球君填充为白色（注意参数），然后另外复制 3 个（对？）雪球君，按照同样的方式，将颜色分别设置为：**<span style="color:#0ff;background-color:black;border-radius:5px">水绿色 R: 0 G:255 B:255</span>**、**<span style="color:#f0f;background-color:black;border-radius:5px">紫色 R: 255 G:0 B:255</span>** 和 **<span style="color:#ff0;background-color:black;border-radius:5px">黄色 R: 255 G:255 B:0</span>**：

   |                 5.a 设置图片格式内部阴影效果                 |             5.b 另复制 3 个雪球君并分别设置颜色              |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707003902034](http://file.cc98.org/v2-upload/lvkhcx1r.png) | ![image-20210707005224161](http://file.cc98.org/v2-upload/5ozvuirj.png) |

6. 新建一张幻灯片，用形状工具中的任意多边形绘制抖动的轨迹（注意起点和终点尽量选择在形状的中央）。然后复制该轨迹，回到第 1 页选中白色雪球君，利用 BrightSlide 插件将该形状粘贴为动作路径：

   |                       6.a 绘制抖动轨迹                       |                   6.b 将形状粘贴为动作路径                   |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707005804738](http://file.cc98.org/v2-upload/1jczzb03.png) | ![image-20210707010328074](http://file.cc98.org/v2-upload/pxnosv4k.png) |

7. 切换到动画标签，激活动画窗格，选中这个刚刚粘贴的动作路径动画，按住 `ctrl`+`shift` 将路径形状缩小到一个合适的水平。接下来重新设置该动画的效果选项（去掉“平滑开始”和“平滑结束”，设置为与“上一动画同时”开始，“非常快”的期间，并且重复“直到幻灯片末尾”）：

   |                     7.a 调整动作路径大小                     |                       7.b 设置效果选项                       |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707010701297](http://file.cc98.org/v2-upload/4pyt2bw5.png) | ![image-20210707011312681](http://file.cc98.org/v2-upload/a1fehqn4.png) |

8. 借助 BrightSlide 插件的“动画刷”工具，将应用在白色雪球君的动画拷贝到其它 3 个颜色的雪球君上（双击“动画刷”可连续应用于多个对象），并将另外 3 个雪球君的动作轨迹依次旋转 90°：

   |              8.a 将动画拷贝到其它 3 个雪球君上               |        8.b 依次旋转 3 个（对？）雪球君的动作轨迹角度         |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707011838627](http://file.cc98.org/v2-upload/g4ectqnb.png) | ![image-20210707012246258](http://file.cc98.org/v2-upload/h5rgi0hc.png) |

9. 将白色雪球君置于顶层，并将所有雪球君都放置在页面中央：

   |                   9.a 将白色雪球君置于顶层                   |               9.b  将所有雪球君放置在页面中央                |
   | :----------------------------------------------------------: | :----------------------------------------------------------: |
   | ![image-20210707012500962](http://file.cc98.org/v2-upload/fhb23y5j.png) | ![image-20210707012957528](http://file.cc98.org/v2-upload/3fn1dtmz.png) |

10. 此时播放幻灯片你已经能够看到抖动的雪球君效果了，但为了制作动图还不够。我们把第二张幻灯片删除，然后将该演示文稿导出为视频，视频分辨率先选一个最高的，时长设置到 2s，格式选择为 mp4：

    |                    10.a 删除第二张幻灯片                     |                  10.b 将演示文稿导出为视频                   |
    | :----------------------------------------------------------: | :----------------------------------------------------------: |
    | ![image-20210707013326531](http://file.cc98.org/v2-upload/gcbqgtwa.png) | ![image-20210707013537857](http://file.cc98.org/v2-upload/iewgvdbw.png) |

11. 一切顺利的情况下，你应该会得到一个和下面这个类似的视频：

    <video src="http://yunban-zw-1251001691.cos.ap-shanghai.myqcloud.com/uploadsoss/file/2021-07-07/2e029d3514600c7a14b2d8ecf0356b84.mp4"  width="50%" controls></video>

12. 打开 ScreenToGif 的编辑器，将这个视频文件导入，帧速率设为 60。等待导入完毕后，全选所有帧（一定注意这一点！），切换到图片标签下，调整图片大小为一个合适数值，如 480×480 px²，然后应用：

    |                12.a 将视频导入到 ScreenToGif                 |                      12.b 调整图片大小                       |
    | :----------------------------------------------------------: | :----------------------------------------------------------: |
    | ![image-20210707014246588](http://file.cc98.org/v2-upload/vg5q5kpm.png) | ![image-20210707014751099](http://file.cc98.org/v2-upload/5dnfgql4.png) |

13. 切换到文件标签下，全选所有帧，另存为 GIF 图片，设置参数参照如下，点击保存，等待存储完毕后，哒啦，大功告成了：

    |                     13.a 另存为 GIF 图片                     |              13.b 成功得到“抖动的雪球君.gif”~~               |
    | :----------------------------------------------------------: | :----------------------------------------------------------: |
    | ![image-20210707015116319](http://file.cc98.org/v2-upload/aolauo1f.png) | ![抖动的雪球君](http://file.cc98.org/v2-upload/vfxkbyqa.gif) |

你是否学会了呢？在此基础上还可以增加更多的效果，比如外发光等，**😜把你的作品跟帖分享出来吧~**

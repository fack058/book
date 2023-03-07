|                             名称                             |       简介       |                             下载                             |                             来源                             |
| :----------------------------------------------------------: | :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                      Win10 business镜像                      |  win10系统镜像   | [🔰](https://tny6h-my.sharepoint.com/:u:/g/personal/jinmingyang_tny6h_onmicrosoft_com/EbETxgOnXF9FrhHXnvqIHmMB2BV1RytiRRS9sHDRhbabrA?e=iKF6KN) | [原版软件](https://next.itellyou.cn/Original/#cbp=Product?ID=f905b2d9-11e7-4ee3-8b52-407a8befe8d1) |
|                            Rufus                             |   系统刻录工具   | [🔰](https://tny6h-my.sharepoint.com/:u:/g/personal/jinmingyang_tny6h_onmicrosoft_com/Ef3NTiqMTUhBrCexWBSHnQ0BPeuuU-ui5We2VpKXHHWsoQ?e=WbeGge) | [![github](https://gcore.jsdelivr.net/gh/fack058/PicGo/gitbook-wodediannao/g.png)](https://github.com/pbatard/rufus) |
|                            Ventoy                            |   系统刻录工具   |  [🔰](https://github.com/ventoy/Ventoy/releases/tag/v1.0.88)  | [![github](https://gcore.jsdelivr.net/gh/fack058/PicGo/gitbook-wodediannao/g.png)](https://github.com/ventoy/Ventoy/releases/tag/v1.0.88) |
| [Bootice](我的电脑/系统/Win系统及其它/Win系统镜像.html#Bootice) | 系统启动修复工具 | [🔰](https://tny6h-my.sharepoint.com/:u:/g/personal/jinmingyang_tny6h_onmicrosoft_com/Efzlj7x-wiNAkTuq581kk6gBaVhml1yOcvmoL2_i6PBngQ?e=r8ovgN) |                         [软件下载]()                         |

# 系统镜像下载

> https://next.itellyou.cn/Original/Index
>
> https://msdn.itellyou.cn/
>
> https://www.microsoft.com/zh-cn/software-download/windows10
>
> https://my.visualstudio.com/Downloads/Featured?mkt=zh-cn
>
> https://www.pcbeta.com/
>
> 推荐 https://next.itellyou.cn/ 网站下载，该网站系统无捆绑软件广告，安装后自动更新系统所需驱动程序，纯净可靠。



---

# 系统版本简介

- ###### **win10 business edition**

  win10 business edition为批量版（也称VOL版）指市面上的win10商业版集合。
  business editions版本包含Education(教育版)、Enterprise (企业版)、Professional(专业版)



- ###### **win10 consumer edition**

  consumer edition则为零售版，指的是市面上的win10普通版本集合。
  business editions版本包含Education(教育版)、Enterprise (企业版)、Professional(专业版)

%accordion%  扩展资料  %accordion%

business edition和consumer edition均是win10的版本集合产品，而win10分有七个版本，具体如下： 

  * ###### 家庭版(Home)：
    
    供家庭用户使用，无法加入Active Directory和Azure AD，不允许远程链接。


  * ###### 专业版(Professional)：
    
    供小型企业使用 在家庭版基础上增加了域账号加入、bitlocker、企业商店等功能。


  * ###### 企业版(Enterprise)：
    
    供中大型企业使用 在专业版基础上增加了DirectAccess，AppLocker等高级企业功能。


  * ###### 教育版(Education)：
    
    供学校使用 (学校职员, 管理人员, 老师和学生) 其功能基本和企业版的一样。


  * ###### 移动版(Mobile)：
    
    面向尺寸较小、配置触控屏的移动设备，例如智能手机和平板电脑，集成有与Windows 10家庭版相同的通用Windows应用和针对触控操作优化的Office


  * ###### 移动企业版(Mobile Enterprise)：
    
    以移动版为基础的企业版本。该版本可以批量允许客户使用，添置企业管理更新功能，以及安全补丁软件的检查与更新功能。


  * ###### 专业工作站版(Windows 10Pro for Workstations)：
    
    该版本重点优化了多核处理以及大文件处理的功能，提供6TB大内存、ReFS文件系统、高速文件共享和工作站模式。


  * ###### 物联网核心版(Windows 10 IoT Core)： 
    
    面向小型低价设备，主要针对物联网设备。

%/accordion%





---

# U盘制作工具

- ##### 开源工具

  * ###### [Ventoy](https://github.com/ventoy/Ventoy/releases/tag/v1.0.88)
    
    简单来说，Ventoy是一个制作可启动U盘的开源工具。有了Ventoy你就无需反复地格式化U盘，你只需要把 ISO/WIM/IMG/VHD(x)/EFI 等类型的文件直接拷贝到U盘里面就可以启动了，无需其他操作。
    
  * ###### [Rufus](https://github.com/pbatard/rufus)
  
    Rufus是一个帮助格式化和创建可启动USB闪存驱动器的工具，如USB钥匙/软盘、记忆棒等。在如下场景中会非常有用：
  
       * 你需要把一些可引导的ISO格式的镜像（Windows，Linux，UEFI等）创建成USB安装盘的时候
  
       * 你需要使用一个还没有安装操作系统的设备的时候
  
       * 你需要从DOS系统刷写BIOS或者其他固件的时候
  
       * 你需要运行一个底层的工具的时候

---


- ##### **第三方商用工具**

  * ###### [微PE ](https://www.wepe.com.cn/download.html)

    谈到良心的PE装机系统，那绝对少不了微PE，首先它占用的内存的比较小，只有200MB左右，其次它的系统纯净，没有像其他PE一样，植入强制性的链接或者广告，可谓是相当良心，最后就是它的操作比较简单，没有那么花里胡哨，对于所有装机用户都比较友好，是很多装机用户的首选PE，毕竟很多人都只追求简单实用，而不过分追求功能有多全面或者有多专业。微PE虽然自身占用的内存小，但是该有的维修工具应有具有，比如BIOS或者UEFI双启、CGI备份还原工具、引导修复和一键理顺盘符等维修工具，还是那句话，实在不会选择的话，就选择微PE吧。

  * ###### [老毛桃PE](http://m.laomaotao.net/) 

     PE装机系统除了微PE外，老毛桃PE也是非常不错的，首先它的制作过程和制造时间比较短，短短几分钟就能完成系统启动盘，它还能一盘两用，在装系统的时候，它是系统盘，而在不装系统的时候，它还可以用来存储数据。前面我们提到了老毛桃的不好之处，那就是会修改主页和携带捆绑软件，老毛桃携带的捆绑软件通常是360全家桶和淘宝，如果用户对修改主页和捆绑软件不那么反感的话，老毛桃反而是一个比较优选的PE，其原因是它的防木马病毒能力比较厉害，不太需要担心系统被木马病毒侵害，老毛桃PE整体来说适中，不算太好也不算太差。

  * ###### [大白菜PE ](https://www.dabaicai.com/)

    大白菜PE是经典的PE装机系统，它相比其他PE的装机系统，它可以一键制作U盘启动盘，具体操作相对比较简单，对于U盘的要求也比较低，所以很多人都用它来装系统或者导数据。大白菜的不好之处和老毛桃类似，都是修改主页和捆绑软件，捆绑软件通常也都是360全家桶和淘宝，大白菜除了个别方面没那么好外，其他方面还是相当不错的，比如内置的维修工具、电脑兼容性等方面都比较优秀。大白菜整体来说表现比较适中，用来装系统或者导数据是完全可以的，只不过在制作启动盘的时候，要把赞助商广告去掉，不然安装系统后会自动安装赞助商的软件。

  * ###### [U盘魔术师PE](https://www.sysceo.com/usm) 

    U盘魔术师和前面提到的PE装机系统不一样，和大白菜、老毛桃相比，U盘魔术师不修改主页和携带捆绑软件，和微PE相比，U盘魔术师的功能相当全面，可以解决各种复杂的情况，如果非要骨头里挑刺说不好的话，可能就是它比较大，单纯安装包就达到2G左右，而其他的PE就相对比较小。U盘魔术师是非常具有特色的PE，比如支持多元化安装模式、具有非常稳定的SRS驱动和可以定制打造专属PE等特色，由于U盘魔术师相对专业或者全面，所以它更适合电脑技术人员，而不那么适合普通装机用户，用户可以根据自己情况选择合适的PE
  



---

# 系统启动引导修复工具

- ###### [Bootice](https://xiazai.zol.com.cn/detail/44/431571.shtml)

  BOOTICE（引导扇区维护工具），用于编辑修改磁盘上的引导扇区的信息，也就是MBR，BOOTICE可在磁盘(硬盘、移动硬盘、U盘、SD卡等)上安装磁盘引导程序。BOOTICE 可用于安装、修复或备份指定磁盘的主引导记录或分区上的引导记录。




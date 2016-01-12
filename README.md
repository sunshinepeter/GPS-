# GPS-
9.4.2  参考资料说明
概述
[1]  http://baike.baidu.com/subview/152851/5072513.htm?fromId=152851&from=rdtself
百度百科对LBS的介绍，读者可了解其“产生背景”一节的内容。
GPS基础知识
GPS基础知识这一节主要的参考资料是GPS Essentials of Satellite Navigation Compendium一书。它是笔者找到的对软件工程师而言关于GPS知识最全面和最通俗易懂的一本书。该书电子版可参考http://www.docin.com/p-67411894.html。
坐标系介绍
[2]  GPS Essentials of Satellite Navigation Compendium第2章“Coordinate systems”
对GPS坐标系相关知识的介绍，读者可先略过投影那几节的内容。
[3]  http://principles.ou.edu/earth_figure_gravity/geoid/
对GPS高度和海拔高度的解释。
时间系统
[4]  《GPS基本原理及其Matlab仿真》第3.2节“GPS时间系统”
时间系统是本章最难讲解的部分了，读者可在本章基础上再做深入学习。
[5]  http://www.doc88.com/p-241652413475.htmlhttp://www.doc88.com/p-241652413475.html
GPS与民用时间的转换
[6]  http://www.hko.gov.hk/gts/time/basicterms-localtimec.htm
香港天文台官方网站对本地时间的介绍
卫星轨道等知识
[7]  GPS Essentials of Satellite Navigation Compendium第3章“Foundations of satellite technology”
GPS基础知识
[8]  http://www.gps.gov/systems/gps/
GPS系统的美国官方网站，内容非常详细和生动，建议读者仔细阅读。
[9]  http://www.gps.gov/systems/gps/space/
GPS官方网站对GPS空间段建设历史的描述。
[10]  http://en.wikipedia.org/wiki/List_of_GPS_satellite_launches
维基百科对GPS卫星发射规划的介绍。
[11]  GPS Essentials of Satellite Navigation Compendium第4章“GNSS technology: the GPS example”
GPS通信频段介绍
[12]  http://www.gps.gov/systems/gps/modernization/civilsignals/#L2C
[13]  http://www.gps.gov/systems/gps/modernization/civilsignals/#L5
GPS官方网站对L2C和L5频段的介绍。
[14]  Interface Specification GPS 705C
该资料是GPS官方规范，用于定义空间段和地面控制段以及用户段通过L5频段交互的接口。如果不需要对L5做进一步了解的话，读者可略过它。
GPS官方规范的下载地址为http://www.gps.gov/technical/
GPS信号介绍
[15]  Understanding the GPS:Introduction to the GPS第2部分“Basic Signal Structure And Error”
这本书是GPS Essentials of Satellite Navigation Compendium一书的升级参考书籍，讲解得非常透彻，覆盖面也比较广，建议读者深入阅读。
GPS导航电文介绍
[16]  Interface Specification GPS 200G
该资料是GPS官方规范，用于定义空间段和地面控制段以及用户段通过L1及L2频段交互的接口。这应该是GPS的核心规范了，建议读者详细阅读。其中，附录II，III和IV详细介绍了GPS卫星发送导航电文的组成及相关参数。
定位计算相关知识
[17]  GPS Essentials of Satellite Navigation Compendium第6章“Calculating position”
[18]  http://www.doc88.com/p-797227641283.html
“GPS测速精度研究及应用”，一篇硕士学位论文，读者权当参考。
[19]  http://wenku.baidu.com/view/3541a8a0b0717fd5360cdcc4.html
中国移动A-GPS终端技术规范。
[20]  http://www.gpsinformation.org/dale/why12.htm
该资料对多channel功能可提升GPS接收器定位速度的原因进行了介绍。
NMEA-0183和GPX
[21]  http://www.doc88.com/p-992198901288.html
NMEA Reference Manual. NMEA规范文档，感兴趣的读者可详细阅读它。
[22]  http://www.topografix.com/gpx.asp
GPX官方网站。GPS格式比较简单，读者可轻松学会它。
[23]  http://en.wikipedia.org/wiki/GPS_eXchange_Format
维基百科对GPX的介绍。
[24]  https://developers.google.com/kml/documentation/
Google关于KML的介绍，上面有一些初学者入门指南资料。
GPS增强系统介绍
[25]  GPS Essentials of Satellite Navigation Compendium第7章“Improved GPS: DGPS, SBAS, A-GPS and HSGPS”
[26]  http://www.tutorialspoint.com/lte/lte_radio_protocol_architecture.htm
Control Plane和User Plane的区别
OMA-SUPL介绍
[27]  OMA Secure User Plane Location Architecture 3.0版
OMA-SUPL官方技术文档，它对SUPL整个架构和相关功能进行了定义，读者务必认真阅读它。
[28]  OMA User Plane Location Protocol 3.0版
ULP协议文档，建议读者认真阅读。
注意，OMA-SUPL相关协议的最高版本为3.0，读者可从官方网站http://technical.openmobilealliance.org/Technical/release_program/supl_V3_0.aspx下载。
[29]  http://wenku.baidu.com/view/cc6b150703d8ce2f006623e2.html
“基于SUPL的移动定位系统的研究和设计”，一篇硕士学位论文，对移动定位技术介绍得非常全面，建议读者认真阅读。
Android中的位置管理
LocationManager应用示例
[30]  https://developer.android.com/google/play-services/location.html
Android SDK中关于Google Play Service中Location API的官方介绍，建议那些对开发高级LBS相关应用程序感兴趣的读者阅读它。
NTP相关
[31]  http://en.wikipedia.org/wiki/Network_Time_Protocol
维基百科关于NTP协议的介绍。
LTO相关
[32]  http://www.broadcom.com/products/GPS/Location-Based-Services/LTO-AGPS
博通公司关于LTO的介绍，建议读者仔细阅读。
数据短信收发
[33]  http://blog.fordemobile.com/2012/09/use-sms-to-send-and-receive-raw-data.html
国外一篇关于如何在Android平台上收发数据短信的文章。

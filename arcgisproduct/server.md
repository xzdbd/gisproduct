ArcGIS for Server
=================
# 产品概述

ArcGIS for Server是基于SOA架构的GIS服务器，通过它可以跨企业或跨互联网以服务形式共享二三维地图、地址定位器、空间数据库和地理处理工具等GIS资源，并允许多种客户端（如Web端、移动端、桌面端等）使用这些资源创建GIS应用。

另外，ArcGIS for Server是您构建云GIS系统的首选，目前已在Amazon上建设了可落地的公有云ArcGIS Online，ArcGIS for Server为私有云的落地也提供了解决方案。

![](../images/server1.jpg?raw=true)

# 产品级别

ArcGIS for Server依据其功能和服务器规模差异，提供了一个可伸缩的产品线。

ArcGIS for Server从功能上分为三个级别的版本：基础版、标准版、高级版。

![](../images/server2.jpg?raw=true)

从功能上分：ArcGIS for Server的三个级别的版本

- 基础版－为用户提供用于空间数据管理的GIS服务器。它主要利用ArcSDE技术来组织和管理地理数据集。并提供发布要素服务用于地图可视化及查询，但不能进行编辑。另外基础版还可以使用几何服务以及发布地理数据服务的能力。基础版不能使用任何扩展。
- 标准版－标准版除包括所有基础版的功能，还包括所有GIS Web服务类型，使用户可以在Web端浏览、使用二三维数据、影像数据以及其他GIS资源。另外标准版支持在线数据编辑，支持将ArcGIS for Desktop标准版包含的各种工具发布为地理处理服务。标准版包括逻辑示意图扩展，以及部分其他扩展，这些扩展需要单独购买。
- 高级版－高级版除包含所有基础版和标准版的功能外，还支持将ArcGIS for Desktop高级版包含的各种工具发布为地理处理服务。为用户提供用于空间数据管理、制图、3D可视化和基于浏览器的编辑、地理处理、空间分析、建模等功能。高级版可以使用任何扩展，部分扩展需要单独购买。

![](../images/server3.jpg?raw=true)

ArcGIS for Server的三种功能级别：基础、标准和高级，功能逐级增强

# 主要功能

**空间数据管理**--ArcGIS for Server具有两种级别的基于相同的ArcGIS Geodatabase模型的地理数据库。借助空间数据服务（Geodata services），管理员可以为发布的地理数据实现抽取，检入/检出（check-in/check-out）以及复制等功能。ArcGIS for Server的三个版本，基础版，标准版和高级版都具有空间数据管理的能力。

**提供丰富Web服务**--ArcGIS for Server提供多种遵循REST、SOAP及OGC标准的Web服务，包括二三维地图服务、影像服务、要素服务、地理处理服务等多种服务类型。并支持使用Server Object Extention（SOE）进行服务自定义扩展，用来满足用户的不同需求。通过Web服务向桌面端、Web端和移动端提供丰富GIS功能。

<table width="560" cellspacing="0" cellpadding="0" align="center" style=" font:12px/2.0 '宋体'; border:1px #666 solid">
    <tbody>
        <tr>
            <th width="250" bgcolor="#dadbdb" align="center" style="border-right:1px #666 solid; border-bottom:1px #666 solid;">即拿即用的ArcGIS Web服务</th>
            <th width="310" bgcolor="#dadbdb" align="center" style=" border-bottom:1px #666 solid;">ArcGIS for Server功能</th>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;2D和3D地图服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供二三维地图服务、缓存服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;影像服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供对栅格影像数据的访问服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;几何服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供对几何图形的操作</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;要素服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供矢量数据编辑服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;地理编码服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供地址与地理位置查询 服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;用于工作流自动化和分析的地理处理服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供空间分析和地理处理服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;空间数据管理服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供对Geodatabase的访问、查询、更新和管理服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;支持SOAP，OGC和KML</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;与面向服务的体系结构集成（SOA）</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; border-bottom:1px #666 solid;">&nbsp;&nbsp;搜索服务</td>
            <td style=" border-bottom:1px #666 solid;">&nbsp;&nbsp;提供对企业级GIS数据资源的检索服务</td>
        </tr>
        <tr>
            <td style="border-right:1px #666 solid; ">&nbsp;&nbsp;逻辑示意图服务</td>
            <td>&nbsp;提供对逻辑示意图的访问服务&nbsp;</td>
        </tr>
    </tbody>
</table>

**空间可视化（制图）**--ArcGIS for Server提供了Web制图服务以支持二维和三维的动态形式或者静态缓存形式的地图发布。GIS的分析人员仅仅点几下鼠标就可以配置一个基于Web制图服务的浏览器应用。另外，ArcGIS的桌面和ArcGIS Explorer可以作为ArcGIS for Server的客户端来浏览二维地图或三维地图。

**在线编辑**--利用ArcGIS for Server可以将存储在企业级空间数据库中的空间和属性数据发布为要素服务，然后在桌面端、Web端或者移动端进行在线数据编辑。

**空间分析和地理处理**--ArcGIS for Server提供了基于服务器的分析和地理处理，包括矢量和栅格分析、3D和网络分析；还支持通过ArcGIS创建的地理处理模型、脚本和工具。

**实时数据处理分析**--ArcGIS for Server通过GeoEvent Processor扩展能够在GIS应用中接入实时数据。可以连接常见传感器，如车载GPS设备、移动设备以及社交媒体供应商，提供了一组卓越的实时过滤、处理以及分析能力。通过它用户可以有效监控重要事件、位置、操作阈值等，并对此进行紧急响应。

**以地图为核心的内容管理**--ArcGIS for Server通过Portal for ArcGIS为用户提供一个可定制的站点，可在自己的IT基础设施中部署实施。Portal for ArcGIS提供了前端扩展了GIS Web服务的使用范围，它集成了地图浏览器及制图工具，并可以搜索和查询GIS资源。

**Web应用**--ArcGIS for Server支持ArcGIS Online、ArcGIS Explorer Online、Esri Maps for Office等多种Web应用程序。同时支持开发人员使用ArcGIS API for JavaScript 、ArcGIS API for Flex 及ArcGIS API for Silverlight来创建自定义的Web应用程序。

**移动应用**--ArcGIS for Server支持iOS、Android、Windows Phone、Windows Mobile等主流移动平台。开发人员可以使用相应的开发工具包创建自定义移动应用。

# 扩展模块

ArcGIS for Server有一系列的可选扩展，补充其核心系统的能力。

![](../images/server4.jpg?raw=true)

ArcGIS GeoEvent Processor for Server是10.2新推出的一个全新扩展，用于实时数据分析处理。

# 系统需求
1\. 支持的操作系统

![](../images/server5.jpg?raw=true)

2\. 硬件要求
对于部署环境，最小内存须4GB。这个要求是基于以下环境的典型部署：

- Two cached map services
- One dynamic map service
- One locator service
- One geoprocessing service
- Geometry service
- PrintingTools service
- SQL Server Express
- IIS with Web Adaptor
- 真正部署时，最低硬件需求并不能具体化，因为要根据用户和需求的不同进行调整。硬件需求必须考虑用户对性能和可扩展性的需求。

# Server 10.2 新特性

ArcGIS 10.2 for Server在其稳定性和功能上都进行了一系列的增强和改进。架构方面，依然采用原生智能云架构，支持Server站点的备份和恢复；功能方面主要包含了与Portal for ArcGIS的集成，原生的数据可以直接发布要素服务；地图、要素、影像、WFS服务可使用标准化的查询；支持将OLE DB 数据源的数据发布服务；新增了ArcGIS GeoEvent Processor for Server扩展模块等。

新特性TOP 5：
- 推出全新的GeoEvent Processor实时数据处理分析扩展，实现实时态势感知；
- 与Portal for ArcGIS集成，将数据托管在本地Server服务器中；
- 提供即拿即用的备份/恢复站点信息功能；
- SDS功能集成到ArcGIS for Server的核心当中，用户可直接连接、编辑原生数据库；
- 新增CachingController 服务，同时提交多个切片任务时能够提高缓存稳定性。

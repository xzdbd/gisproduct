ArcGIS Engine
=============
# 产品概述

*	在许多应用中，用户需要通过定制应用或者在现有应用中增添GIS逻辑来实现对GIS的需求，这些应用程序常常是运行在Windows和Linux上，ArcGIS Engine就被用来建立这样一些应用程序。ArcGIS Engine是ArcObjects组件跨平台应用的核心集合，它提供多种开发的接口，可以适应.NET，Java和C++等开发环境。开发者可以使用这些组件来开发和GIS相关的地图应用，包括从简单的地图浏览到高级的GIS编辑程序。

# 主要功能

- **ArcGIS Engine 可以开发嵌入式应用**
	如在我们的业务系统中需要相关的GIS功能，或者在字处理文档和电子表格中嵌入GIS功能，比如在Excel添加地图控制功能。
- **ArcGIS Engine 可以开发独立的GIS应用**
	可以开发一个完全独立的GIS应用，比如：数据入库系统。
- **ArcGIS Engine 可以和ENVI集成**
	实现GIS和遥感的一体化应用，比如：土地利用变化监测系统。
- **ArcGIS Engine支持平板电脑并开发高级的编辑功能**
	注重于GIS字段编辑的应用程序（定制的轻量级ArcGIS for Desktop应用）。
- **ArcGIS Engine根据用户需求可以开发出含有专业的GIS功能的应用
	如包含网络分析，空间分析，3D分析等。**
- **ArcGIS Engine可以作为ArcGIS for Server或者ArcGIS Online的客户端**
	可以访问SOAP或者REST方式的服务（ArcGIS 10.1 新增对REST服务访问的接口）。

总之，有了ArcGIS Engine，开发人员可以更灵活性的开发出自己想要的GIS应用程序。开发人员可以使用Microsoft .NET，C++或者Java等众多交互式开发环境行业标准中的一种来建立独有的应用程序或者将ArcGIS Engine嵌入到现有的软件中来专门处理GIS的应用。

![](../images/engine.png?raw=true)

# 关键技术

ArcGIS Engine包括许多可以用来进行定制应用程序开发的用户接口和工具(在ArcObjects软件库中)。
- ArcGIS Engine开发工具包（ArcGIS Engine Developer Kit）是由开发人员来开发客户化应用程序的一系列工具，这个工具包是EDN软件协议的一部分。
- ArcGIS Engine（以前是ArcGIS Engine 运行时，ArcGIS Engine Runtime，在ArcGIS 10.1中改名为ArcGIS Engine）是一组包含ArcGIS Engine核心组件的工具，以及扩展模块。它能够为最终用户提供一个运行 ArcGIS Engine开发的应用程序的环境。

ArcGIS Engine运行时是根据部署的软件数量而独立销售的运行时许可。安装有ArcGIS for Desktop的计算机允许运行需要ArcGIS Engine运行时的应用程序，因此ArcGIS for Desktop（Basic，Standard或Advanced）的用户可以运行由ArcGIS Engine 开发的程序。其它想要使用由ArcGIS Engine开发的应用程序的用户则必须 购买并安装ArcGIS Engine运行时软件。
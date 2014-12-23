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

# 系统需求
1. ArcGIS 10.1 Engine系统需求

1.1 支持的操作系统

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.0 '宋体';">
    <tbody>
        <tr>
            <th width="420" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持的操作系统</th>
            <th width="90" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">最低版本</th>
            <th width="90" bgcolor="#e2e2e2" align="center" style=" border-bottom:1px #CCC solid; ">最高版本</th>
        </tr>
        <tr>
            <td width="420" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Red Hat Enterprise Linux Server 5 (32-bit and 64-bit)</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Update  7 or higher with libX11-1.0.3-11 patch</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid;">Latest maintenance update</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Red Hat Enterprise Linux Server 6 (32-bit and 64-bit)</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Update 1</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid;">Latest maintenance update</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;SUSE Linux Enterprise Server 11 (32-bit and 64-bit)</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP1</td>
            <td align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2003 Standard, Enterprise, and Datacenter<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2008 Standard, Enterprise, and Datacenter<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2008 R2 Standard, Enterprise, and Datacenter<br>
            &nbsp;(64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP1</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2012 Standard, and Datacenter (64-bit [EM64T]) **</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows 8 Basic, Professional and Enterprise<br>
            &nbsp;(32-bit and 64-bit [EM64T])**</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows 7 Ultimate, Enterprise, Professional, Home Premium<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP1</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Vista Ultimate, Enterprise, Business, Home Premium<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows XP Professional Edition, Home Edition (32-bit)</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP3</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP3</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows XP Professional Edition, Home Edition (64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
    </tbody>
</table>

1.2 硬件条件

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.5 '宋体';">
    <tbody>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;CPU速度</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;2.2 GHz minimum ; Hyper-threading (HHT) or Multi-core recommended</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;处理器</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;Intel Pentium 4, Intel Core Duo, or Xeon Processors; SSE2 minimum<br>
            &nbsp;On Windows: Run this <a href="http://technet.microsoft.com/en-us/sysinternals/cc835722" target="_blank" style="color:#2D7104">Microsoft utility</a> from your Windows command prompt to<br>
            &nbsp;check your processor. <br>
            &nbsp;See <a href="http://support.esri.com/en/knowledgebase/techarticles/detail/31903" target="_blank" style="color:#2D7104">Dual or dual-core support policy</a></td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;内存</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;至少2 GB</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;显示属性</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;24-bit color depth</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;屏幕分辨率</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;1024 x 768 recommended minimum at normal size (96 dpi)</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;交换空间</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;Determined by the operating system; 500 MB minimum.</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;磁盘空间(仅<br>
            &nbsp;限于Runtime)</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;<strong>Windows:</strong> 2 GB <br>
            &nbsp;<strong>Linux:</strong> 2 GB <br>
            &nbsp;ArcGIS Engine will create cache files when used; additional disk space <br>
            &nbsp;may be required.</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;&nbsp;显卡</td>
            <td width="500" style="border-bottom:1px #CCC solid;">&nbsp;<a href="http://cyri.systemrequirementslab.com/cyri_if/1186/10913" target="_blank" style="color:#2D7104">Check your computer's ability to run ArcGIS</a> <br>
            &nbsp;64 MB RAM minimum, 256 MB RAM recommended. NVIDIA, ATI, and Intel <br>
            &nbsp;chipsets supported.<br>
            &nbsp;24-bit capable graphics accelerator<br>
            &nbsp;<strong>Windows:</strong>OpenGL version 2.0 runtime minimum is required, and Shader Model 3.0 or <br>
            &nbsp;higher is recommended<br>
            <strong>&nbsp;Linux: </strong>OpenGL version 2.0 runtime minimum with Shader Model 2.0 minimum is <br>
            &nbsp;required, Shader Model 3.0 or higher is recommended. <br>
            &nbsp;Be sure to use the latest available driver.</td>
        </tr>
        <tr>
            <td width="100" bgcolor="#eeece0" style="border-right:1px #CCC solid;">&nbsp;&nbsp;用户接口</td>
            <td width="500">&nbsp;<strong>Linux:</strong> X Windows with Gnome or KDE Desktop Environment is required.</td>
        </tr>
    </tbody>
</table>

1.3 软件条件

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.5 '宋体';">
    <tbody>
        <tr>
            <td width="110" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Python<br>
            &nbsp;Requirement for<br>
            &nbsp;Geoprocessing</td>
            <td width="490" style="border-bottom:1px #CCC solid;">&nbsp;ArcGIS Engine geoprocessing tools require that Python 2.7.x and Numerical <br>
            &nbsp;Python 1.6.x are installed. If the ArcGIS Engine setup does not find either <br>
            &nbsp;Python 2.7.x or Numerical Python (NumPy) 1.6.x installed on the target <br>
            &nbsp;computer, Python 2.7.2 and Numerical Python 1.6.1 will be installed during a <br>
            &nbsp;complete installation. You can choose a Custom installation to unselect the <br>
            &nbsp;Python feature and avoid installing it. Additionally, if the Python setup is <br>
            &nbsp;executed during the ArcGIS Engine installation, you will be provided with the <br>
            &nbsp;opportunity to choose its installation location. The Python installation <br>
            &nbsp;location should not include spaces.</td>
        </tr>
        <tr>
            <td width="110" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Microsoft .NET<br>
            &nbsp;Framework<br>
            &nbsp;Requirement</td>
            <td width="490" style="border-bottom:1px #CCC solid;">&nbsp;<strong>Windows:</strong><a href="http://resources.arcgis.com/en/help/system-requirements/10.1/index.html#//01510000007t000000" target="_blank" style="color:#2D7104">Microsoft .NET Framework 3.5 Service Pack 1</a> must be installed for <br>
            &nbsp;solutions developed using the Microsoft .NET Framework.</td>
        </tr>
        <tr>
            <td width="110" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Java<br>
            &nbsp;Requirement</td>
            <td width="490" style="border-bottom:1px #CCC solid;">&nbsp;Java Runtime Environment (JRE) version 6 update 20 (32 bit) is required for <br>
            &nbsp;solutions developed using the Java Platform.</td>
        </tr>
        <tr>
            <td width="10" style="border-right:1px #CCC solid;">&nbsp;Browser<br>
            &nbsp;Requirement</td>
            <td width="490">&nbsp;<strong>Windows:</strong> ArcGIS Engine requires a minimum installation of Microsoft Internet <br>
            &nbsp;Explorer Version 7.0 or 8.0. If you do not have an installation of Microsoft<br>
            &nbsp;Internet Explorer Version 7.0/8.0, you must obtain and install it prior to <br>
            &nbsp;installing ArcGIS Engine.<br>
            &nbsp;<strong>Linux:</strong> ArcGIS Engine requires a minimum installation of the latest version of<br>
            &nbsp;Mozilla Firefox. If you do not have an installation of Mozilla Firefox, it is <br>
            &nbsp;recommended you obtain and install it prior to installing ArcGIS Engine.</td>
        </tr>
    </tbody>
</table>

1.4 连接数据库管理系统的需求条件

你的客户端机器(例如,一个运行ArcMap的机器)将需要有适当您正在使用的关系型数据库的客户端文件。这些客户端文件可从各自的RDBMS供应商获取,但它们也可作为便利从Esri客户服务门户作获取。请参阅数据库客户端获取更多信息。从客户服务们或获取的客户端文件是IBM DB2、Oracle、IBM Informix PostgreSQL,微软SQL Server,和微软Windows Azure的SQL数据库。客户服务门户中没有Netezza和Teradata,必须从IBM和Teradata支持网站获取。

1.5 许可管理器的需求条件

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.0 '宋体';">
    <tbody>
        <tr>
            <th width="420" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持的操作系统</th>
            <th width="90" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">最低版本</th>
            <th width="90" bgcolor="#e2e2e2" align="center" style=" border-bottom:1px #CCC solid; ">最高版本</th>
        </tr>
        <tr>
            <td width="420" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Red Hat Enterprise Linux Server 5 (32-bit and 64-bit)</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Update 7 or higher with libX11-1.0.3-11 patch</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Red Hat Enterprise Linux Server 6 (32-bit and 64-bit)*</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Update 1</td>
            <td align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td width="420" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Sun Solaris 10 (64-bit [SPARC])*</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Maintenance update 4 (8/07)</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;SUSE Linux Enterprise Server 11 (32-bit and 64-bit)*</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP1</td>
            <td align="center" style="border-bottom:1px #CCC solid;">&nbsp;</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2003 Standard, Enterprise, and Datacenter<br>
            &nbsp;(32-bit and 64-bit [EM64T]) (including R2)</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2008 Standard, Enterprise, and Datacenter<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Server 2008 R2 Standard, Enterprise, and Datacenter<br>
            &nbsp;(64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP1</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows Vista Ultimate, Enterprise, Business, Home Premium<br>
            &nbsp;(32-bit and 64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP2</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP2</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows 7 Ultimate, Enterprise, Professional, Home Premium <br>
            &nbsp;(32-bit and64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP1</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;Windows XP Professional Edition, Home Edition (32-bit)</td>
            <td align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">SP3</td>
            <td align="center" style="border-bottom:1px #CCC solid;">SP3</td>
        </tr>
        <tr>
            <td style="border-right:1px #CCC solid; ">&nbsp;Windows XP Professional Edition, Home Edition (64-bit [EM64T])</td>
            <td align="center" style="border-right:1px #CCC solid;">SP2</td>
            <td align="center">SP2</td>
        </tr>
    </tbody>
</table>

*许可管理服务器和软件授权向导需要安装OpenGl

ArcGIS 10.1的许可管理器的硬件需求很ArcGIS Engine的硬件需求一样

2. 开发SDK需求

2.1 支持的操作系统

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.0 '宋体';">
    <tbody>
        <tr>
            <td width="150" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持的操作系统</td>
            <td width="90" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">最低版本</td>
            <td width="90" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">最高版本</td>
            <td width="90" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">rcObjects SDK for the Java 平台</td>
            <td width="90" bgcolor="#e2e2e2" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;ArcObjects<br>
            &nbsp;SDK for 跨平<br>
            &nbsp;台 C++</td>
            <td width="90" bgcolor="#e2e2e2" style="border-bottom:1px #CCC solid; ">&nbsp;ArcObjects<br>
            &nbsp;SDK for.NET <br>
            &nbsp;Framework</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Red Hat Enterprise<br>
            &nbsp;Linux Server 5<br>
            &nbsp;(32-bit and 64-bit)</td>
            <td width="90" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Update 7<br>
            &nbsp;with libX11<br>
            &nbsp;-1.0.3-11<br>
            &nbsp;patch</td>
            <td width="90" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Latest<br>
            &nbsp;maintenance<br>
            &nbsp;update</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">不支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Red Hat Enterprise<br>
            &nbsp;Linux Server 6 <br>
            &nbsp;(32-bit and 64-bit)</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Update1</td>
            <td width="90" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Latest<br>
            &nbsp;maintenance<br>
            &nbsp;update</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">不支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;SUSE Linux Enterprise <br>
            &nbsp;Server 11 <br>
            &nbsp;(32-bit and 64-bit))</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;SP1</td>
            <td width="90" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">不支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows Server 2003 <br>
            &nbsp;Standard, Enterprise, <br>
            &nbsp;and Datacenter (32-bit <br>
            &nbsp;and 64-bit [EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows Server 2008 <br>
            &nbsp;Standard, Enterprise, <br>
            &nbsp;and Datacenter (32-bit <br>
            &nbsp;and 64-bit [EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows Server 2008 R2 <br>
            &nbsp;Standard, Enterprise, <br>
            &nbsp;and Datacenter <br>
            &nbsp;(64-bit [EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP1</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows Server 2012 <br>
            &nbsp;Standard, and <br>
            &nbsp;Datacenter (64-bit <br>
            &nbsp;[EM64T]) **</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows 8 Basic, <br>
            &nbsp;Professional and <br>
            &nbsp;Enterprise (32-bit <br>
            &nbsp;and 64-bit [EM64T])**</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows 7 Ultimate, <br>
            &nbsp;Enterprise, <br>
            &nbsp;Professional, Home <br>
            &nbsp;Premium (32-bit and <br>
            &nbsp;64-bit [EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP1</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows Vista <br>
            &nbsp;Ultimate, Enterprise, <br>
            &nbsp;Business, Home Premium <br>
            &nbsp;(32-bit and 64-bit <br>
            &nbsp;[EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Windows XP <br>
            &nbsp;Professional Edition, <br>
            &nbsp;Home Edition (32-bit)</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP3</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">SP3</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持</td>
            <td width="90" align="center" style="border-bottom:1px #CCC solid; ">支持</td>
        </tr>
        <tr>
            <td width="150" style="border-right:1px #CCC solid;  ">&nbsp;Windows XP <br>
            &nbsp;Professional Edition,<br>
            &nbsp;Home Edition <br>
            &nbsp;(64-bit [EM64T])</td>
            <td width="90" align="center" style="border-right:1px #CCC solid;  ">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid;">SP2</td>
            <td width="90" align="center" style="border-right:1px #CCC solid;  ">支持</td>
            <td width="90" align="center" style="border-right:1px #CCC solid;  ">支持</td>
            <td width="90" align="center">支持</td>
        </tr>
    </tbody>
</table>

*请参阅操作系统需求和限制部分获取更多的需求信息

** ArcGIS 10.1 SP1开始支持.

2.2 硬件需求

<table width="600" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.5 '宋体';">
    <tbody>
        <tr>
            <td width="300" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;</td>
            <td width="150" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">Microsoft Windows</td>
            <td width="150" bgcolor="#e2e2e2" align="center" style=" border-bottom:1px #CCC solid;">Linux</td>
        </tr>
        <tr>
            <td width="300" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;ArcObjects SDK for the Java 平台</td>
            <td width="150" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">630 MB</td>
            <td width="150" align="center" style=" border-bottom:1px #CCC solid;">648 MB</td>
        </tr>
        <tr>
            <td width="300" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">&nbsp;ArcObjects SDK for 跨平台 C++</td>
            <td width="150" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid;">670 MB</td>
            <td width="150" align="center" style=" border-bottom:1px #CCC solid;">588 MB</td>
        </tr>
        <tr>
            <td width="300" style="border-right:1px #CCC solid;">&nbsp;ArcObjects SDK for the Microsoft .NET Framework</td>
            <td width="150" align="center" style="border-right:1px #CCC solid;">938 MB</td>
            <td width="1500" align="center">Not Applicable</td>
        </tr>
    </tbody>
</table>

2.3 开发人员解决方案 (SDK) 需求

<table width="660" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.0 '宋体';">
    <tbody>
        <tr>
            <th width="140" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">ArcObjects SDK</th>
            <th width="380" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">支持和推荐的 IDE</th>
            <th width="140" bgcolor="#e2e2e2" align="center" style=" border-bottom:1px #CCC solid; ">SDK需求</th>
        </tr>
        <tr>
            <td width="140" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;ArcObjects SDK for<br>
            &nbsp;the Java Platform</td>
            <td width="380" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;ArcObjects SDK for the Java Platform提供的开发者集成环境插件<br>
            &nbsp;通过模板、代码片段,和项目向导增强开发人员的经验，ArcObjects <br>
            &nbsp;SDK for the Java Platform支持的IDE如下:(注Visual beans用户必<br>
            &nbsp;须手动安装Visual Editor)。<br>
            &nbsp;-	Eclipse Helios (3.6) SR1 and SR2 IDE for Java EE <br>
            &nbsp;&nbsp;Developers <br>
            &nbsp;-	Eclipse Helios (3.6) SR1 and SR2 IDE for Java Developers <br>
            &nbsp;-	Eclipse Indigo (3.7) SR1 IDE for Java Developers</td>
            <td width="140" style=" border-bottom:1px #CCC solid; ">&nbsp;ArcGIS for Desktop, <br>
            &nbsp;ArcGIS Engine, or <br>
            &nbsp;ArcGIS for Server is <br>
            &nbsp;required to develop <br>
            &nbsp;with ArcObjects SDK.<br>
            &nbsp;Java Development Kit <br>
            &nbsp;(JDK) version 6 <br>
            &nbsp;update 20 (32-bit for <br>
            &nbsp;Desktop and Engine or <br>
            &nbsp;64-bit for Server) <br>
            &nbsp;and above.</td>
        </tr>
        <tr>
            <td width="140" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;ArcObjects SDK for <br>
            &nbsp;Cross Platform C++</td>
            <td width="380" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">
            <table width="360" cellspacing="0" cellpadding="0" align="center" style="font:12px/2.0 '宋体';">
                <tbody>
                    <tr>
                        <td width="360" height="30"><strong>Supported Widget Toolkit(s)</strong></td>
                    </tr>
                    <tr>
                        <td><strong>注意：</strong>仅仅支持Qt3.3.8 和 4.2.3的商业许可</td>
                    </tr>
                    <tr>
                        <td width="360">
                        <table width="350" cellspacing="0" cellpadding="0" align="center" style=" border:1px #CCC solid; font:12px/2.0 '宋体';">
                            <tbody>
                                <tr>
                                    <th width="115" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;</th>
                                    <th width="120" bgcolor="#e2e2e2" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">Windows</th>
                                    <th width="115" bgcolor="#e2e2e2" align="center" style=" border-bottom:1px #CCC solid; ">Linux</th>
                                </tr>
                                <tr>
                                    <td width="115" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">Motif</td>
                                    <td width="120" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">Not Applicable</td>
                                    <td width="115" align="center" style=" border-bottom:1px #CCC solid; ">2.2.3</td>
                                </tr>
                                <tr>
                                    <td width="115" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">GTK</td>
                                    <td width="120" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">2.4.14</td>
                                    <td width="115" align="center" style=" border-bottom:1px #CCC solid; ">2.4.13</td>
                                </tr>
                                <tr>
                                    <td width="115" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">QT3</td>
                                    <td width="120" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">3.3.8</td>
                                    <td width="115" align="center" style=" border-bottom:1px #CCC solid; ">3.3.8</td>
                                </tr>
                                <tr>
                                    <td width="115" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">QT4</td>
                                    <td width="120" align="center" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">4.7.3</td>
                                    <td width="115" align="center" style=" border-bottom:1px #CCC solid; ">4.7.3</td>
                                </tr>
                                <tr>
                                    <td width="115" align="center" style="border-right:1px #CCC solid;">WX</td>
                                    <td width="120" align="center" style="border-right:1px #CCC solid;  ">2.8.7</td>
                                    <td width="115" align="center">2.8.7-GTK</td>
                                </tr>
                            </tbody>
                        </table>
                        </td>
                    </tr>
                    <tr>
                        <td><strong>Windows的额外需求</strong><br>
                        Microsoft Visual Studio 2010 (C++) Professional, <br>
                        Premium, Ultimate Edition (有或者无SP1)</td>
                    </tr>
                </tbody>
            </table>
            </td>
            <td width="140" style=" border-bottom:1px #CCC solid; ">&nbsp;ArcGIS Engine is <br>
            &nbsp;required to develop <br>
            &nbsp;with ArcObjects SDK. <br>
            &nbsp;<strong>Windows:</strong> Microsoft <br>
            &nbsp;.NET Framework 3.5 <br>
            &nbsp;Service Pack 1</td>
        </tr>
        <tr>
            <td width="140" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;ArcObjects SDK for <br>
            &nbsp;the Microsoft .NET <br>
            &nbsp;Framework</td>
            <td width="380" style="border-right:1px #CCC solid; border-bottom:1px #CCC solid; ">&nbsp;Microsoft Visual Studio 2010 (C#, VB.NET) Professional, <br>
            &nbsp;Premium, Ultimate Edition<br>
            &nbsp;Microsoft Visual Studio 2010 Visual Basic Express<br>
            &nbsp;Microsoft Visual Studio 2010 Visual C# Express <br>
            &nbsp;<strong>注意： </strong><br>
            &nbsp;Visual Studio 2010 或者Visual Studio 2010 sp1 都被支持</td>
            <td width="140" style=" border-bottom:1px #CCC solid;">&nbsp;ArcGIS for Desktop, <br>
            &nbsp;ArcGIS Engine, or <br>
            &nbsp;ArcGIS for Server is <br>
            &nbsp;required to develop<br>
            &nbsp;with ArcObjects SDK.  <br>
            &nbsp;Microsoft .NET <br>
            &nbsp;Framework 3.5 <br>
            &nbsp;Service Pack 1</td>
        </tr>
    </tbody>
</table>

3. 操作系统限制

3.1 操作系统限制—所有平台

当运行在64位环境中, ArcGIS for Desktop,ArcGIS Engine和ArcReader是最为32位应用程序。可参阅ArcGIS 10.1 产品是否支持64位处理器。

3.2 操作系统限制—Windows

- Winows7上的ArcGIS 开发帮助系统需要 Adobe Reader 9.1.2 或者更高. 参阅KB37244 获取更多信息。
- ArcGlobe/ArcScene and any other 3D application generally will not work over Remote Desktop or other Windows Terminal Services clients, because they do not support 3D graphics acceleration.
- ArcGlobe/ArcScene 和其它3D应用程序通常不会通过远程桌面或者Windows Terminal 服务终端客户端工作，因为它们不支持3D显卡加速。

3.3 操作系统限制—Linux

和ArcGIS Engine相关产品的产品只支持Linux x86(也就是，CPU符合x86体系结构)与支持的Linux版本。 这是一个要求，操作系统(二进制)不被修改。Esri不支持任何支持开发人员释放的任何操作系统。

**Red Hat Enterprise Linux Server 5**

Red Hat Enterprise Linux Server 5 Update 7 (32位和64位)与最低libX11-1.0.3-11补丁将被支持，只要它是来自红帽，对最新内核/ glibc版本没有任何修改。

需要下面的包:

The Base System > X Window System—all package groups

The Base System > Legacy Software Support group, including the following from Optional Packages:
-	compat-libstdc++-33
-	compat-libstdc++-296
-	compat-libf2c
-	compat-libgcc-296
-	compat-openldap-2.3

The Development > Development Tools—all package groups

The Development > Legacy Software Development—all package groups

The Development > X Software Development group - all package groups

The Optionals Repository > freeglut -2.4
-	libXp and libXp-devel packages
-	libXtst and libXtst-devel packages

The following additional software packages are required:
-	cairo
-	compat-libf2c-34 (Fortran 77 compatibility)
-	compat-gcc-34
-	GNU arbitrary precision library - gmp-4 package
-	GNU C Library (glibc) 2.5
-	gkt2-2.10 and gtk2-devel-2.10
-	libgfortran44*
-	libidn
-	libstdc++-4.1
-	OpenGL package: including mesa-libGL-6.5* and mesa-libGLU-6.5*
-	Openldap package: openldap
-	Openssl package: openssl

注意：所有包的版本都必须和列出的一样或者更高

在x86_64平台上，如果上面32位版本的包是可用的，它们必须在安装ArcGIS之前安装

**Red Hat Enterprise Linux Server 6**

Red Hat Enterprise Linux Server 6 Update 1 (32位和64位)最低将被支持，只要它是来自红帽，对最新内核/ glibc版本没有任何修改。

需要下面的包:

The Base System > X Window System—all package groups

The Base System > Legacy Software Support group, including the following from Optional Packages:
-	compat-libstdc++-3.3
-	compat-libstdc++-296
-	compat-libf2c

The Development > Development Tools—all package groups

The Development > Legacy Software Development—all package groups

The Development > X Software Development group - all package groups
-	libXp and libXp-devel packages
-	libXtst and libXtst-devel packages

The Optionals Repository > freeglut -2.4

The LSB base libraries support for Red Hat Enterprise Linux: redhat-lsb-4.0-3

The following additional software packages are required:
-	cairo
-	compat-libf2c-34 (Fortran 77 compatibility)
-	compat-gcc-34
-	GNU arbitrary precision library - gmp-4 package
-	GNU libc Libraries (glibc) 2.12
-	gtk2-2.10 and gtk2-devel-2.10
-	libgfortran44*
-	libidn
-	libstdc++-4.4
-	OpenGL package: including mesa-libGL-6.5* and mesa-libGLU-6.5*
-	Openldap package: openldap
-	Openssl package: openssl

注意：所有包的版本都必须和列出的一样或者更高

在x86_64平台上，如果上面32位版本的包是可用的，它们必须在安装ArcGIS之前安装

**SuSE Linux Enterprise Server 11**

SUSE Linux Enterprise Server的Linux 补丁 (32位和64位)将被支持，只要它是来SUSE Linux，对最新内核/ glibc版本没有任何修改。

需要下面的包:

From Development > Languages > Fortran group
-	libg2c33
-	libgfortran43*

From Development > Libraries > X11 group
-	cairo
-	gtk and gtk-devel version 2.18 minimum
-	Openmotif package— openmotif and openmotif-devel

From the System/Libraries group
-	compat-dapl
-	freeglut and freeglut-devel
-	GNU C Library (glibc) package version 2.3.4-2 minimum
-	GNU MP Library - gmp package
-	libidn package
-	Mesa: includes libGL and libGLU
-	xorg-x11-libs package: includes libXtst
-	xorg-X11-libXp package

From the System/X11/Servers/XF86_4 group
-	xorg-x11-server
-	xorg-x11-server-extra: includes Xvfb

The following additional software packages are required:
-	OpenLDAP Client Libraries: includes libldap-2 and openldap2-client
-	SSL Security package: includes openssl and libopenssl-devel

注意：所有包的版本都必须和列出的一样或者更高

在x86_64平台上，如果上面32位版本的包是可用的，它们必须在安装ArcGIS之前安装
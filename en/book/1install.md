# 1.0 Install\/Uninstall

No special measures necessary, follow the standard installation process - extract the module folder into the

```
/modules 
```

directory in your XOOPS installation. Install the module through Admin -&gt; System Module -&gt; Modules.

Detailed instructions on installing modules are available in the **[Chapter 2.12 of our XOOPS Operations Manual](https://www.gitbook.com/book/xoops/xoops-operations-guide/)**

## _**Requirements**_

A working ImpressCMS or XOOPS content management system (see below.)

Web server with PHP support. PHP version 5.0 or greater is strongly recommended.

MySQL database server version 4.1 or greater. Version 5.0 or greater recommended.

TCPDF Version 5.2.000 or greater recommended (see below.)

### **Content Management System**

Gwloto is implemented as a module for either ImpressCMS or XOOPS. Both of these are content management systems, and they will be described generically in this documentation as "CMS" unless commenting on specific unique features.

Gwloto has been tested with ImpressCMS version 1.2.2. Other versions may work, but this is the only version tested and officially supported.

For more information on ImpressCMS, see: http://www.impresscms.org/

ImpressCMS is also available from the Microsoft Web Apps Gallery, see: http:\/\/www.microsoft.com\/web\/gallery\/ImpressCMS.aspx

Gwloto has been tested with XOOPS version 2.4.5. Other versions may work, but this is the only version tested and officially supported.

For more information on XOOPS, see: http://www.xoops.org/

### **TCPDF**

Many of the supplied plugins provide PDF output. PDDF output is generated using a PHP library called TCPDF. ImpressCMS (as of version 1.2.2) includes an older version of TCPDF. Gwloto will function with this version, but there will noticeable issues with some plugins. For best results, we recommend installation of the current version of TCPDF

Gwloto will look for TCPDF in the modules/gwloto/tcpdf/ directory. You can also direct gwloto to load TCPDF from any location with a module preference setting.

For more information on TCPDF, see: http://www.tcpdf.org/


# Introduction #

The core classes module contain the implementation of messages and classes that provide persistence<sup>(todo)</sup>, transformations and reporting. This page shows how to install this module.

# Pre-requisites #

## System Requirements ##
Supported Operating Systems: Windows Server 2003; Windows Server 2008; Windows Vista; Windows XP
Installed Software: Visual Studio 2008 Enterprise Edition (.NET Framework version 3.5 Service Pack 1)

# Installation #

There are two methods of installation:

  * Via Setup Wizard;
  * Via simple File Copy.

# Setup Wizard Install #

1)Download the `Setup_CoreClasses1001.zip` (1001 = version number) archive and decompress it to a temporary directory;<br>
2)Run the setup program <code>Setup1001.msi</code>;<br>
3)Select a destination directory to the assemblies (.dll);<br>
4)Choose Everyone.<br>
<br>
<h1>File Copy Install</h1>

Download the <code>bin1001.zip</code> (1001 = version number) archive and decompress it to the installation directory.<br>
<br>
<h1>Remarks</h1>

1)If your program executes in a directory other that the installation directory, the assemblies must be installed on the GAC (Global Assembly Cache).  This may be done by using the .NET Framework 2.0 Configuration tool located on the Administrative Tools Menu, or by using gacutil.exe (Microsoft<sup>(R)</sup> .NET Global Assembly Cache Utility);<br><br>
2)The only thing that you have to make sure of in both cases is that all assembly files (.dll) of this module MUST be located on the same directory.<br>
<br>
<br>
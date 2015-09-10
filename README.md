﻿## FinalBuilder Team Foundation Build Task

A [Team Foundation Build](https://msdn.microsoft.com/Library/vs/alm/Build/overview) task for running [FinalBuilder](https://www.finalbuilder.com/downloads/finalbuilder) projects. FinalBuilder provides a graphical IDE and command line to create, debug, and run software build projects.  

The FinalBuilder task brings to Team Foundation Build over 700 actions for common software delivery tasks. Notable groups of these actions include;

* Build logic - If..Then, Try..Catch..Finally, Switch, While, Iterator, and Async
* Version control - AccuRev, CVS, Git, ClearCase, JediVCS, Mercurial, TFS, Plastic SCM, PureCM, Perforce, QVCS, Subversion, Surround, and Sourcegear Vault
* Compilers - Visual Studio .Net, Delphi, Java, and Visual Basic
* Build - Ant, NAnt, MSBuild, and Maven
* Testing - NUnit, MbUnit, MSTest\VSTest, TestComplete, AQTest, and Typemock
* Installer - InnoSetup, InstallAware, Wise, InstallAnywhere, GP Install, NullSoft, InstallShield, Advanced Installer, Setup Factory, Wix, and MSI
* Deployment - Web Deploy, EC2, IIS, FTP, and SFTP
* Configuration - .Net, HyperV, VWWare, XML, Windows OS, and IIS

*Currently the FinalBuilder task is only available for Windows platforms.* 

For detailed installation installations refer to the [Installation Steps](https://github.com/VSoftTechnologies/FinalBuilderTFS/blob/master/docs/Installation.md).

## Quick Help

### Cloning

Use git to clone this repository to a location of your choice. 

`
git clone https://github.com/VSoftTechnologies/FinalBuilderTFS.git
`

### Installation

Installation requires use of the tfx-cli tool provided by Microsoft. Refer to the [Installation Steps](https://github.com/VSoftTechnologies/FinalBuilderTFS/blob/master/docs/Installation.md) for detailed instructions if your unfamiliar with this tool. 

`
tfx login
tfx build tasks upload ./FinalBuilder --overwrite
`
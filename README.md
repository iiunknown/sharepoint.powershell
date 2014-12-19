#sharepoint.powershell
> SharePoint管理，开发，测试等方面相关的Powershell脚本集合。

## solution.deployment.ps1
> Sharepoint解决方案包部署脚本。

### 适用版本 
- SharePoint 2010
- SharePoint 2013

### 使用方式
1. 下载脚本[solution.deployment.ps1](solution.deployment.ps1)。
2. 复制`solution.deployment.ps1`脚本到需要部署的解决方案包所在的目录。
3. 修改脚本中第121行中的`$solutionNames`变量值，多个解决方案包使用`分号(;)`隔开。![需要修改的变量](imgs/solution.deployment.1.png)
4. 在Powershell命令行窗口执行`solution.deployment.ps1`。![需要修改的变量](imgs/solution.deployment.2.png)


## list.export2csv.ps1
> 导出列表数据到csv文件，以便借助Excel等工具进行数据分析。SharePoint在UI上提供了列表数据导出到Excel的功能，但是受数据量，超时时间等影响（目前没有找到官方确认说法，继续搜寻中）。使用此脚本可以避免这样的风险，而且还可以扩展代码进行导出前一定业务逻辑的处理。

### 适用版本 
- SharePoint 2010
- SharePoint 2013

### 使用方式
1. 下载脚本[list.export2csv.ps1](list.export2csv.ps1)。
2. 参考下载脚本中的注释提示，按照实际需要修改脚本。
3. 在Powershell命令窗口中运行脚本文件。
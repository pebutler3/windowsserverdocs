---
title: Ftp: send_1
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 000aa80a-60a0-4b51-815f-3237a4f3e0f4 vhorne
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Ftp: send_1

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Copies a local file to the remote computer using the current file transfer type.   
## Syntax  
```  
send <LocalFile> [<RemoteFile>]  
```  
### Parameters  
|Parameter|Description|  
|-------|--------|  
|<LocalFile>|Specifies the local file to copy.|  
|<RemoteFile>|Specifies the name to use on the remote computer.|  
## Remarks  
-   The **send** command is identical to the **put** command.  
-   If *RemoteFile* is not specified, the file is given the *LocalFile* name.  
## <a name="BKMK_Examples"></a>Examples  
Copy the local file **test.txt** and name it **test1.txt** on the remote computer.  
```  
send test.txt test1.txt  
```  
Copy the local file **program.exe** to the remote computer.  
```  
send program.exe  
```  
## Additional references  
-   [Command-Line Syntax Key](Command-Line-Syntax-Key.md)  
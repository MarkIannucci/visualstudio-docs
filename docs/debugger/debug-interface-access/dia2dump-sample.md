---
title: "Dia2dump Sample | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "sample applications [DIA SDK]"
  - "Dia2dump sample [DIA SDK]"
ms.assetid: 492c0893-7043-452f-a020-890a47230d20
caps.latest.revision: 12
author: "mikejo5000"
ms.author: "mikejo"
manager: ghogen
ms.workload: 
  - "multiple"
---
# Dia2dump Sample
The Dia2dump sample is installed with Visual Studio and contains the Dia2dump.cpp source file. The compiled executable runs from the command line and displays the contents of an entire program database (.pdb) file.  
  
### To install the sample  
  
1.  Verify that your system meets all setup requirements described in the Visual Studio Setup start page.  
  
2.  Install Visual Studio and follow all setup and installation instructions for the included samples.  
  
#### To build the sample  
  
1.  Open the Dia2dump.sln file in Visual Studio. (If necessary, Visual Studio will first help you upgrade the Dia2dump project.)  
  
2.  In the project property pages, in the **C/C++** &#124; **General** &#124; **Additional Include Directories** property, specify the `..\DIA SDK\include` directory. This guarantees that the compiler can find the dia2.h file.  
  
3.  On the **Build** menu, click **Rebuild Solution**.  
  
4.  Close Visual Studio.  
  
#### To run the sample  
  
1.  Open a command prompt and type the following:  
  
    ```  
    dia2dump filename  
    ```  
  
## See Also  
 [Dia2dump.cpp Source File](../../debugger/debug-interface-access/dia2dump-cpp-source-file.md)   
 [Port, Migrate, and Upgrade Visual Studio Projects](../../porting/port-migrate-and-upgrade-visual-studio-projects.md)
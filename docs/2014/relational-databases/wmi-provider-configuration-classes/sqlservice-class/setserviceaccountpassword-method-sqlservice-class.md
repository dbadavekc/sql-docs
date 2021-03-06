---
title: "SetServiceAccountPassword Method (SqlService Class) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
api_name: 
  - "SetServiceAccountPassword Method (SqlService Class)"
api_location: 
  - "sqlmgmproviderxpsp2up.mof"
topic_type: 
  - "apiref"
helpviewer_keywords: 
  - "SetServiceAccountPassword method"
ms.assetid: e577a1ac-985c-4799-bb38-9393efc3def2
caps.latest.revision: 36
author: CarlRabeler
ms.author: carlrab
manager: craigg
---
# SetServiceAccountPassword Method (SqlService Class)
  Modifies the password for the account that the referenced service runs under.  
  
## Syntax  
  
```  
  
object  
.SetServiceAccountPassword(  
AccountOldPassword , ServiceStartPassword  
)  
  
```  
  
## Parts  
 *object*  
 A [SqlService Class](sqlservice-class.md) object that represents the service.  
  
#### Parameters  
 *AccountOldPassword*  
 A string value that specifies the existing password for the account.  
  
 *ServiceStartPassword*  
 A string value that specifies the new password for the account.  
  
## Property Value/Return Value  
 A `uint32` value, which is 0 if the service was successfully modified, 1 if the request is not supported, and any other number to indicate an error.  
  
## Remarks  
  

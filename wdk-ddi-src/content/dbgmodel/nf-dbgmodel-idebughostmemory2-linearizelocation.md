---
UID: NF:dbgmodel.IDebugHostMemory2.LinearizeLocation
title: IDebugHostMemory2::LinearizeLocation
author: windows-driver-content
description: TBD
ms.assetid: 2c835fe9-e18e-4847-a377-70cf5058f98c
ms.author: windowsdriverdev
ms.date: 09/18/2018
ms.topic: method
ms.keywords: IDebugHostMemory2::LinearizeLocation, LinearizeLocation, IDebugHostMemory2.LinearizeLocation, IDebugHostMemory2::LinearizeLocation, IDebugHostMemory2.LinearizeLocation
req.header: dbgmodel.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
-	apiref
api_type: 
-	COM
api_location: 
-	dbgmodel.h
api_name: 
-	IDebugHostMemory2.LinearizeLocation
product: Windows
targetos: Windows


tech.root: debugger
---

# IDebugHostMemory2::LinearizeLocation


## -description

Takes a location which may represent something other than a virtual memory address and attempts to linearize the location into a virtual memory address within the given context.  This operation may fail if the location cannot be represented by a virtual address (e.g.: it's a register). 

## -parameters

### -param context

### -param location

### -param pLinearizedLocation


## -returns
This method returns HRESULT which indicates success or failure.

## -remarks

## -see-also

[IDebugHostMemory2 interface](nn-dbgmodel-idebughostmemory2.md)
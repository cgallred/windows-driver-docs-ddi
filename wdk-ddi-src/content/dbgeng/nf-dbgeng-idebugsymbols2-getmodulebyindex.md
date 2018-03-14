---
UID: NF:dbgeng.IDebugSymbols2.GetModuleByIndex
title: IDebugSymbols2::GetModuleByIndex method
author: windows-driver-content
description: The GetModuleByIndex method returns the location of the module with the specified index.
old-location: debugger\getmodulebyindex.htm
old-project: debugger
ms.assetid: a33f8a78-4026-4424-af42-2ad359054556
ms.author: windowsdriverdev
ms.date: 2/27/2018
ms.keywords: GetModuleByIndex method [Windows Debugging], GetModuleByIndex method [Windows Debugging], IDebugSymbols interface, GetModuleByIndex method [Windows Debugging], IDebugSymbols2 interface, GetModuleByIndex method [Windows Debugging], IDebugSymbols3 interface, GetModuleByIndex,IDebugSymbols2.GetModuleByIndex, IDebugSymbols interface [Windows Debugging], GetModuleByIndex method, IDebugSymbols2, IDebugSymbols2 interface [Windows Debugging], GetModuleByIndex method, IDebugSymbols2::GetModuleByIndex, IDebugSymbols3 interface [Windows Debugging], GetModuleByIndex method, IDebugSymbols3::GetModuleByIndex, IDebugSymbols::GetModuleByIndex, IDebugSymbols_0406a71f-e9eb-4acd-93e8-1637ee2506df.xml, dbgeng/IDebugSymbols2::GetModuleByIndex, dbgeng/IDebugSymbols3::GetModuleByIndex, dbgeng/IDebugSymbols::GetModuleByIndex, debugger.getmodulebyindex
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: method
req.header: dbgeng.h
req.include-header: Dbgeng.h
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	COM
api_location:
-	dbgeng.h
api_name:
-	IDebugSymbols.GetModuleByIndex
-	IDebugSymbols2.GetModuleByIndex
-	IDebugSymbols3.GetModuleByIndex
product: Windows
targetos: Windows
req.typenames: DOT4_ACTIVITY, *PDOT4_ACTIVITY
---

# IDebugSymbols2::GetModuleByIndex method


## -description


The <b>GetModuleByIndex</b> method returns the location of the module with the specified index.


## -syntax


````
HRESULT GetModuleByIndex(
  [in]  ULONG    Index,
  [out] PULONG64 Base
);
````


## -parameters




### -param Index [in]

Specifies the index of the module whose location is requested.


### -param Base [out]

Receives the location in the target's memory address space of the module.


## -returns



This method may also return other error values.  See <a href="https://msdn.microsoft.com/713f3ee2-2f5b-415e-9908-90f5ae428b43">Return Values</a> for more details.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method was successful.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_FALSE</b></dt>
</dl>
</td>
<td width="60%">
The specified module was not loaded, and information about the module was not available.

</td>
</tr>
</table>
 




## -remarks



For more information about modules, see <a href="https://msdn.microsoft.com/library/windows/hardware/ff552231">Modules</a>.



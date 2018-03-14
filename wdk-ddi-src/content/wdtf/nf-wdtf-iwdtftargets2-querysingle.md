---
UID: NF:wdtf.IWDTFTargets2.QuerySingle
title: IWDTFTargets2::QuerySingle method
author: windows-driver-content
description: Returns a single item from the collection.
old-location: dtf\iwdtftargets2_querysingle.htm
old-project: dtf
ms.assetid: d9aa36b6-8ce4-41dd-96a8-104fa9094405
ms.author: windowsdriverdev
ms.date: 2/23/2018
ms.keywords: IWDTFTargets2, IWDTFTargets2 interface [Windows Device Testing Framework], QuerySingle method, IWDTFTargets2::QuerySingle, Microsoft.WDTF.IWDTFTargets2.QuerySingle, Microsoft::WDTF::IWDTFTargets2::QuerySingle, QuerySingle method [Windows Device Testing Framework], QuerySingle method [Windows Device Testing Framework], IWDTFTargets2 interface, QuerySingle,IWDTFTargets2.QuerySingle, dtf.iwdtftargets2_querysingle, wdtf/IWDTFTargets2::QuerySingle
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: method
req.header: wdtf.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: Windows XP Professional
req.target-min-winversvr: Windows Server 2008
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WDTF.idl
req.max-support: 
req.namespace: Microsoft.WDTF
req.assembly: WDTF.Interop.metadata_dll
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
-	WDTF.Interop.metadata_dll.dll
api_name:
-	IWDTFTargets2.QuerySingle
product: Windows
targetos: Windows
req.typenames: TTraceLevel
req.product: Windows 10 or later.
---

# IWDTFTargets2::QuerySingle method


## -description


Returns a single item from the collection.


## -syntax


````
HRESULT QuerySingle(
  [in]          BSTR         SDEL,
  [out, retval] IWDTFTarget2 **ppTarget
);
````


## -parameters




### -param SDEL [in]

The SDEL query string.


### -param ppTarget [out, retval]

The requested item.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also

<a href="..\wdtf\nn-wdtf-iwdtftargets2.md">IWDTFTargets2</a>



 

 

<a href="mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback [dtf\dtf]:%20IWDTFTargets2::QuerySingle method%20 RELEASE:%20(2/23/2018)&amp;body=%0A%0APRIVACY STATEMENT%0A%0AWe use your feedback to improve the documentation. We don't use your email address for any other purpose, and we'll remove your email address from our system after the issue that you're reporting is fixed. While we're working to fix this issue, we might send you an email message to ask for more info. Later, we might also send you an email message to let you know that we've addressed your feedback.%0A%0AFor more info about Microsoft's privacy policy, see http://privacy.microsoft.com/en-us/default.aspx." title="Send comments about this topic to Microsoft">Send comments about this topic to Microsoft</a>

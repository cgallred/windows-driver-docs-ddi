---
UID: NN:dbgmodel.IDebugHostModuleSignature
title: IDebugHostModuleSignature (dbgmodel.h)
description: Represents a module signature -- a definition which will match a set of modules by name and/or version.
ms.date: 07/13/2018
keywords: ["IDebugHostModuleSignature interface"]
req.header: dbgmodel.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
tech.root: debugger
ms.custom: RS5
f1_keywords:
 - IDebugHostModuleSignature
 - dbgmodel/IDebugHostModuleSignature
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - dbgmodel.h
api_name:
 - IDebugHostModuleSignature
---

# IDebugHostModuleSignature interface


## -description

Represents a module signature -- a definition which will match a set of modules by name and/or version.

## -inheritance

IDebugHostModuleSignature inherits from IUnknown.

## -remarks

Module signatures represent a means to check whether a given module meets a set of criteria regarding naming and versioning. A module signature is created via the CreateModuleSignature method on [IDebugHostSymbols](nn-dbgmodel-idebughostsymbols.md). It can match the module name, and an optional range of version numbers for the module. Once such a signature is created, the client receives an IDebugHostModuleSignature interface.

## -see-also

[Debugger Data Model C++ Overview](/windows-hardware/drivers/debugger/data-model-cpp-overview)

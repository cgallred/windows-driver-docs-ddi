---
UID: NC:d3d12umddi.PFND3D12DDI_ADD_TO_STATE_OBJECT_0072
title: PFND3D12DDI_ADD_TO_STATE_OBJECT_0072 (d3d12umddi.h)
description: Learn more about the PFND3D12DDI_ADD_TO_STATE_OBJECT_0072 callback function.
ms.date: 05/03/2024
keywords: ["PFND3D12DDI_ADD_TO_STATE_OBJECT_0072 callback function"]
req.header: d3d12umddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 2004
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
targetos: Windows
tech.root: display
ms.custom: 
f1_keywords:
 - PFND3D12DDI_ADD_TO_STATE_OBJECT_0072
 - d3d12umddi/PFND3D12DDI_ADD_TO_STATE_OBJECT_0072
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3d12umddi.h
api_name:
 - PFND3D12DDI_ADD_TO_STATE_OBJECT_0072
dev_langs:
 - c++
---

# PFND3D12DDI_ADD_TO_STATE_OBJECT_0072 callback function

## -description

**PFND3D12DDI_ADD_TO_STATE_OBJECT_0072** incrementally adds to an existing state object.

## -parameters

### -param unnamedParam1

A handle to the display device (graphics context).

### -param unnamedParam2 [in]

Pointer to a [**D3D12DDIARG_ADD_TO_STATE_OBJECT_0072**](ns-d3d12umddi-d3d12ddiarg_add_to_state_object_0072.md) structure containing subobject(s) to add to a state object.

### -param unnamedParam3

Handle to a state object.

### -param unnamedParam4

Handle to a runtime handle type state object.

## -returns

Returns HRESULT.

## -remarks

A state object is created via [**PFND3D12DDI_CREATE_STATE_OBJECT_0054**](nc-d3d12umddi-pfnd3d12ddi_create_state_object_0054.md).

See the [DirectX Raytracing (DXR) functional specification](https://microsoft.github.io/DirectX-Specs/d3d/Raytracing.html) for more information.

## -see-also

[**D3D12DDIARG_ADD_TO_STATE_OBJECT_0072**](nc-d3d12umddi-pfnd3d12ddi_add_to_state_object_0072.md)

[**PFND3D12DDI_CREATE_STATE_OBJECT_0054**](nc-d3d12umddi-pfnd3d12ddi_create_state_object_0054.md)

---
UID: NS:sidebandaudio._SIDEBANDAUDIO_SUPPORTED_FORMATS
title: _SIDEBANDAUDIO_SUPPORTED_FORMATS
author: windows-driver-content
description: 
ms.assetid: 3aaefd01-561e-42be-859c-240f1305b266
ms.author: windowsdriverdev
ms.date: 09/07/2018
ms.topic: struct
ms.prod: windows-hardware
ms.technology: windows-devices
ms.keywords: _SIDEBANDAUDIO_SUPPORTED_FORMATS, SIDEBANDAUDIO_SUPPORTED_FORMATS, *PSIDEBANDAUDIO_SUPPORTED_FORMATS, 
req.header: sidebandaudio.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.ddi-compliance:
req.unicode-ansi:
req.max-support:
req.typenames: SIDEBANDAUDIO_SUPPORTED_FORMATS, *PSIDEBANDAUDIO_SUPPORTED_FORMATS
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	sidebandaudio.h
api_name: 
-	_SIDEBANDAUDIO_SUPPORTED_FORMATS
product: Windows
targetos: Windows
---

# _SIDEBANDAUDIO_SUPPORTED_FORMATS structure

## -description
 Describes the formats supported by the Audio Endpoint.

## -struct-fields

### -field CbSize
Size of structure including storage for Formats Array allocated after the struct.
 
### -field EpIndex
 0 based index indicating the Endpoint on device.
 
### -field NumFormats
Number of KSDATAFORMAT structures.
 
### -field Formats
Array of pointers of KSDATAFORMAT.

## -remarks

## -see-also
[sidebandaudio.h](index.md)
---
Description: 'Specifies the inheritance relationship for a service.'
ms.assetid: 'e7f5314a-75e8-4f36-8e18-d614eda7a097'
title: 'WPD\_SERVICE\_INHERITANCE\_TYPES enumeration'
---

# WPD\_SERVICE\_INHERITANCE\_TYPES enumeration

The **WPD\_SERVICE\_INHERITANCE\_TYPES** enumeration type specifies the inheritance relationship for a service.

## Syntax


```C++
typedef enum tagWPD_SERVICE_INHERITANCE_TYPES { 
  WPD_SERVICE_INHERITANCE_IMPLEMENTATION��= 0
} WPD_SERVICE_INHERITANCE_TYPES;
```



## Constants

<dl> <dt>

<span id="WPD_SERVICE_INHERITANCE_IMPLEMENTATION"></span><span id="wpd_service_inheritance_implementation"></span>**WPD\_SERVICE\_INHERITANCE\_IMPLEMENTATION**
</dt> <dd>

The service inherits by implementing an abstract service definition.

</dd> </dl>

## Requirements



|                   |                                                                                             |
|-------------------|---------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>PortableDevice.h</dt> </dl> |



## See also

<dl> <dt>

[**IPortableDeviceServiceCapabilities::GetInheritedServices**](iportabledeviceservicecapabilities-getinheritedservices.md)
</dt> </dl>

�

�




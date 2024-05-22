---
title: UmbracoCommerceOrderStatusController
description: API reference for UmbracoCommerceOrderStatusController in Umbraco Commerce
---
## UmbracoCommerceOrderStatusController

```csharp
public class UmbracoCommerceOrderStatusController : UmbracoCommerceAuthorizedJsonControllerBase
```

**Inheritance**

* Class [UmbracoCommerceAuthorizedJsonControllerBase](umbracocommerceauthorizedjsoncontrollerbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Web.Controllers](README.md)

### Constructors

#### UmbracoCommerceOrderStatusController

```csharp
public UmbracoCommerceOrderStatusController(IBackOfficeSecurityAccessor backOfficeSecurityAccesor, 
    UmbracoCommerceContext ctx)
```


### Methods

#### CreateOrderStatus

```csharp
public IActionResult CreateOrderStatus(Guid storeId)
```


---

#### DeleteOrderStatus

```csharp
public IActionResult DeleteOrderStatus(Guid orderStatusId)
```


---

#### GetOrderStatus

```csharp
public IActionResult GetOrderStatus(Guid orderStatusId)
```


---

#### GetOrderStatuses

```csharp
public IActionResult GetOrderStatuses(Guid storeId)
```


---

#### SaveOrderStatus

```csharp
public IActionResult SaveOrderStatus(OrderStatusSaveDto orderStatus)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
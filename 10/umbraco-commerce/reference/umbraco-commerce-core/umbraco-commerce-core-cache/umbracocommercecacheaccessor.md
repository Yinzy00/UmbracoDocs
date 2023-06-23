---
title: UmbracoCommerceCacheAccessor
description: API reference for UmbracoCommerceCacheAccessor in Umbraco Commerce
---
## UmbracoCommerceCacheAccessor

```csharp
public class UmbracoCommerceCacheAccessor : ICacheAccessor
```

**Inheritance**

* interface [ICacheAccessor](icacheaccessor.md)

**Namespace**
* [Umbraco.Commerce.Core.Cache](README.md)

### Constructors

#### UmbracoCommerceCacheAccessor

```csharp
public UmbracoCommerceCacheAccessor(IPolicyCache runtimeCache, ICache requestCache, 
    EntityCaches entityCaches, Lazy<IUnitOfWorkAccessor> uowAccessor)
```


### Properties

#### EntityCaches

```csharp
public EntityCaches EntityCaches { get; }
```


---

#### RequestCache

```csharp
public ICache RequestCache { get; }
```


---

#### RuntimeCache

```csharp
public IPolicyCache RuntimeCache { get; }
```


---

#### ScopedEntityCaches

```csharp
public EntityCaches ScopedEntityCaches { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
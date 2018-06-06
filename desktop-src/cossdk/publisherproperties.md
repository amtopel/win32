---
Description: Contains an object for each publisher property for the parent SubscriptionsForComponent collection.
ms.assetid: 7699c258-ca11-4652-b2f7-b2f2307c01fc
title: PublisherProperties collection
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# PublisherProperties collection

Contains an object for each publisher property for the parent [**SubscriptionsForComponent**](subscriptionsforcomponent.md) collection.

This collection supports the [**Add**](/windows/desktop/api/ComAdmin/nf-comadmin-icatalogcollection-add) and [**Remove**](/windows/desktop/api/ComAdmin/nf-comadmin-icatalogcollection-remove) methods of the [**COMAdminCatalogCollection**](/windows/desktop/api/ComAdmin/) object.

## Members

The **PublisherProperties** collection inherits from the [**IUnknown**](https://msdn.microsoft.com/library/windows/desktop/ms680509) interface but does not have additional members.

## Related Collections

You can navigate from this collection to any of the following collections:

-   [**ErrorInfo**](errorinfo.md)
-   [**PropertyInfo**](propertyinfo.md)
-   [**RelatedCollectionInfo**](relatedcollectioninfo.md)

You can navigate to this collection from the following collections:

-   [**SubscriptionsForComponent**](subscriptionsforcomponent.md)

## Properties

The following properties are supported by the [**COMAdminCatalogObject**](/windows/desktop/api/ComAdmin/) object within the collection:

-   [Name](#name)
-   [Value](#value)

### Name



|                |                                                                                                                                                                                                                                                                        |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Description    | The name of the property. Extra spaces at the beginning and end of the string are stripped out. This property is returned when the [**Key**](/windows/desktop/api/ComAdmin/nf-comadmin-icatalogobject-get_key) or [**Name**](/windows/desktop/api/ComAdmin/nf-comadmin-icatalogobject-get_name) property method is called on an object of this collection. |
| Access         | WriteOnce                                                                                                                                                                                                                                                              |
| Type           | String                                                                                                                                                                                                                                                                 |
| Default        | "New Property"                                                                                                                                                                                                                                                         |
| Minimum system | Windows 2000                                                                                                                                                                                                                                                           |



 

### Value



|                |                           |
|----------------|---------------------------|
| Description    | A value for the property. |
| Access         | ReadWrite                 |
| Type           | Variant                   |
| Default        | N/A                       |
| Minimum system | Windows 2000              |



 

## See also

<dl> <dt>

[COM+ Administration Collections](com--administration-collections.md)
</dt> </dl>

 

 



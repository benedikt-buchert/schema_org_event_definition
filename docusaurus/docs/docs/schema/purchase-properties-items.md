# Untitled array in purchase Schema

```txt
https://example.com/purchase.schema.json#/properties/items
```

Items associated with the event

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                            |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [purchase.schema.json\*](../../../../out/purchase.schema.json "open original schema") |

## items Type

`object[]` ([product](purchase-properties-items-product.md))

## items Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

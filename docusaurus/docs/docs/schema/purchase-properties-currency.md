# Untitled string in purchase Schema

```txt
https://example.com/purchase.schema.json#/properties/currency
```

Currency of the items associated with the event

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                            |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [purchase.schema.json\*](../../../../out/purchase.schema.json "open original schema") |

## currency Type

`string`

## currency Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Z]{3}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Z%5D%7B3%7D%24 "try regular expression with regexr.com")

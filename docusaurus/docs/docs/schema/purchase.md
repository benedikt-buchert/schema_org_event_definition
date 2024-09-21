# purchase Schema

```txt
https://example.com/purchase.schema.json
```

Definition of a GA4 purchase event

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [purchase.schema.json](../../../../out/purchase.schema.json "open original schema") |

## purchase Type

`object` ([purchase](purchase.md))

# purchase Properties

| Property                           | Type     | Required | Nullable       | Defined by                                                                                                              |
| :--------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------- |
| [transaction\_id](#transaction_id) | `string` | Required | cannot be null | [purchase](purchase-properties-transaction_id.md "https://example.com/purchase.schema.json#/properties/transaction_id") |
| [value](#value)                    | `number` | Required | cannot be null | [purchase](purchase-properties-value.md "https://example.com/purchase.schema.json#/properties/value")                   |
| [currency](#currency)              | `string` | Required | cannot be null | [purchase](purchase-properties-currency.md "https://example.com/purchase.schema.json#/properties/currency")             |
| [coupon](#coupon)                  | `string` | Optional | cannot be null | [purchase](purchase-properties-coupon.md "https://example.com/purchase.schema.json#/properties/coupon")                 |
| [shipping](#shipping)              | `number` | Optional | cannot be null | [purchase](purchase-properties-shipping.md "https://example.com/purchase.schema.json#/properties/shipping")             |
| [tax](#tax)                        | `number` | Optional | cannot be null | [purchase](purchase-properties-tax.md "https://example.com/purchase.schema.json#/properties/tax")                       |
| [items](#items)                    | `array`  | Required | cannot be null | [purchase](purchase-properties-items.md "https://example.com/purchase.schema.json#/properties/items")                   |

## transaction\_id

The unique identifier of a transaction

`transaction_id`

* is required

* Type: `string`

* cannot be null

* defined in: [purchase](purchase-properties-transaction_id.md "https://example.com/purchase.schema.json#/properties/transaction_id")

### transaction\_id Type

`string`

## value

The monetary value of the event

`value`

* is required

* Type: `number`

* cannot be null

* defined in: [purchase](purchase-properties-value.md "https://example.com/purchase.schema.json#/properties/value")

### value Type

`number`

### value Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## currency

Currency of the items associated with the event

`currency`

* is required

* Type: `string`

* cannot be null

* defined in: [purchase](purchase-properties-currency.md "https://example.com/purchase.schema.json#/properties/currency")

### currency Type

`string`

### currency Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Z]{3}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Z%5D%7B3%7D%24 "try regular expression with regexr.com")

## coupon

The coupon name/code associated with the event

`coupon`

* is optional

* Type: `string`

* cannot be null

* defined in: [purchase](purchase-properties-coupon.md "https://example.com/purchase.schema.json#/properties/coupon")

### coupon Type

`string`

## shipping

Shipping cost associated with a transaction

`shipping`

* is optional

* Type: `number`

* cannot be null

* defined in: [purchase](purchase-properties-shipping.md "https://example.com/purchase.schema.json#/properties/shipping")

### shipping Type

`number`

### shipping Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## tax

Tax cost associated with a transaction

`tax`

* is optional

* Type: `number`

* cannot be null

* defined in: [purchase](purchase-properties-tax.md "https://example.com/purchase.schema.json#/properties/tax")

### tax Type

`number`

### tax Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## items

Items associated with the event

`items`

* is required

* Type: `object[]` ([product](purchase-properties-items-product.md))

* cannot be null

* defined in: [purchase](purchase-properties-items.md "https://example.com/purchase.schema.json#/properties/items")

### items Type

`object[]` ([product](purchase-properties-items-product.md))

### items Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

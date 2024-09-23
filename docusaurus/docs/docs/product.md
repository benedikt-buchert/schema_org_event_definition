## product Type

`object` ([product](product.md))

# product Properties

| Property                            | Type          | Required | Nullable       | Defined by                                                                                                            |
| :---------------------------------- | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------- |
| [item\_id](#item_id)                | `string`      | Required | cannot be null | [product](product-properties-item_id.md "https://examples.com/product.schema.json#/properties/item_id")               |
| [item\_name](#item_name)            | `string`      | Required | cannot be null | [product](product-properties-item_name.md "https://examples.com/product.schema.json#/properties/item_name")           |
| [affiliation](#affiliation)         | `string`      | Optional | cannot be null | [product](product-properties-affiliation.md "https://examples.com/product.schema.json#/properties/affiliation")       |
| [coupon](#coupon)                   | `string`      | Optional | cannot be null | [product](product-properties-coupon.md "https://examples.com/product.schema.json#/properties/coupon")                 |
| [discount](#discount)               | `number`      | Optional | cannot be null | [product](product-properties-discount.md "https://examples.com/product.schema.json#/properties/discount")             |
| [index](#index)                     | `number`      | Optional | cannot be null | [product](product-properties-index.md "https://examples.com/product.schema.json#/properties/index")                   |
| [item\_brand](#item_brand)          | `string`      | Optional | cannot be null | [product](product-properties-item_brand.md "https://examples.com/product.schema.json#/properties/item_brand")         |
| [item\_category](#item_category)    | `string`      | Optional | cannot be null | [product](product-properties-item_category.md "https://examples.com/product.schema.json#/properties/item_category")   |
| [item\_category2](#item_category2)  | `string`      | Optional | cannot be null | [product](product-properties-item_category2.md "https://examples.com/product.schema.json#/properties/item_category2") |
| [item\_category3](#item_category3)  | `string`      | Optional | cannot be null | [product](product-properties-item_category3.md "https://examples.com/product.schema.json#/properties/item_category3") |
| [item\_category4](#item_category4)  | `string`      | Optional | cannot be null | [product](product-properties-item_category4.md "https://examples.com/product.schema.json#/properties/item_category4") |
| [item\_category5](#item_category5)  | Not specified | Optional | cannot be null | [product](product-properties-item_category5.md "https://examples.com/product.schema.json#/properties/item_category5") |
| [item\_list\_id](#item_list_id)     | `string`      | Optional | cannot be null | [product](product-properties-item_list_id.md "https://examples.com/product.schema.json#/properties/item_list_id")     |
| [item\_list\_name](#item_list_name) | `string`      | Optional | cannot be null | [product](product-properties-item_list_name.md "https://examples.com/product.schema.json#/properties/item_list_name") |
| [item\_variant](#item_variant)      | `string`      | Optional | cannot be null | [product](product-properties-item_variant.md "https://examples.com/product.schema.json#/properties/item_variant")     |
| [location\_id](#location_id)        | `string`      | Optional | cannot be null | [product](product-properties-location_id.md "https://examples.com/product.schema.json#/properties/location_id")       |
| [price](#price)                     | `number`      | Required | cannot be null | [product](product-properties-price.md "https://examples.com/product.schema.json#/properties/price")                   |
| [quantity](#quantity)               | `number`      | Required | cannot be null | [product](product-properties-quantity.md "https://examples.com/product.schema.json#/properties/quantity")             |

## item\_id

The ID of the item.

`item_id`

* is required

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_id.md "https://examples.com/product.schema.json#/properties/item_id")

### item\_id Type

`string`

### item\_id Examples

```json
"SKU_12345"
```

## item\_name

The name of the item.

`item_name`

* is required

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_name.md "https://examples.com/product.schema.json#/properties/item_name")

### item\_name Type

`string`

### item\_name Examples

```json
"Stan and Friends Tee"
```

## affiliation

A product affiliation to designate a supplying company or brick and mortar store location

`affiliation`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-affiliation.md "https://examples.com/product.schema.json#/properties/affiliation")

### affiliation Type

`string`

### affiliation Examples

```json
"Google Store"
```

## coupon

The coupon name/code associated with the item

`coupon`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-coupon.md "https://examples.com/product.schema.json#/properties/coupon")

### coupon Type

`string`

### coupon Examples

```json
"SUMMER_FUN"
```

## discount

The unit monetary discount value associated with the item

`discount`

* is optional

* Type: `number`

* cannot be null

* defined in: [product](product-properties-discount.md "https://examples.com/product.schema.json#/properties/discount")

### discount Type

`number`

### discount Examples

```json
2.22
```

## index

The index/position of the item in a list

`index`

* is optional

* Type: `number`

* cannot be null

* defined in: [product](product-properties-index.md "https://examples.com/product.schema.json#/properties/index")

### index Type

`number`

### index Examples

```json
5
```

## item\_brand

The brand of the item

`item_brand`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_brand.md "https://examples.com/product.schema.json#/properties/item_brand")

### item\_brand Type

`string`

### item\_brand Examples

```json
"Google"
```

## item\_category

The category of the item. If used as part of a category hierarchy or taxonomy then this will be the first category

`item_category`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_category.md "https://examples.com/product.schema.json#/properties/item_category")

### item\_category Type

`string`

### item\_category Examples

```json
"Apparel"
```

## item\_category2

The second category hierarchy or additional taxonomy for the item

`item_category2`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_category2.md "https://examples.com/product.schema.json#/properties/item_category2")

### item\_category2 Type

`string`

### item\_category2 Examples

```json
"Adult"
```

## item\_category3

The third category hierarchy or additional taxonomy for the item

`item_category3`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_category3.md "https://examples.com/product.schema.json#/properties/item_category3")

### item\_category3 Type

`string`

### item\_category3 Examples

```json
"Shirts"
```

## item\_category4

The fourth category hierarchy or additional taxonomy for the item

`item_category4`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_category4.md "https://examples.com/product.schema.json#/properties/item_category4")

### item\_category4 Type

`string`

### item\_category4 Examples

```json
"Crew"
```

## item\_category5

The fifth category hierarchy or additional taxonomy for the item

`item_category5`

* is optional

* Type: unknown

* cannot be null

* defined in: [product](product-properties-item_category5.md "https://examples.com/product.schema.json#/properties/item_category5")

### item\_category5 Type

unknown

### item\_category5 Examples

```json
"Short sleeve"
```

## item\_list\_id

The ID of the list in which the item was presented to the user

`item_list_id`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_list_id.md "https://examples.com/product.schema.json#/properties/item_list_id")

### item\_list\_id Type

`string`

### item\_list\_id Examples

```json
"related_products"
```

## item\_list\_name

The name of the list in which the item was presented to the user

`item_list_name`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_list_name.md "https://examples.com/product.schema.json#/properties/item_list_name")

### item\_list\_name Type

`string`

### item\_list\_name Examples

```json
"Related products"
```

## item\_variant

The item variant or unique code or description for additional item details/options

`item_variant`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-item_variant.md "https://examples.com/product.schema.json#/properties/item_variant")

### item\_variant Type

`string`

### item\_variant Examples

```json
"The item variant or unique code or description for additional item details/options"
```

## location\_id

The physical location associated with the item

`location_id`

* is optional

* Type: `string`

* cannot be null

* defined in: [product](product-properties-location_id.md "https://examples.com/product.schema.json#/properties/location_id")

### location\_id Type

`string`

### location\_id Examples

```json
"ChIJIQBpAG2ahYAR_6128GcTUEo"
```

## price

The monetary unit price of the item, in units of the specified currency parameter

`price`

* is required

* Type: `number`

* cannot be null

* defined in: [product](product-properties-price.md "https://examples.com/product.schema.json#/properties/price")

### price Type

`number`

### price Constraints

**minimum**: the value of this number must greater than or equal to: `0`

### price Examples

```json
"10.01"
```

## quantity

Item quantity

`quantity`

* is required

* Type: `number`

* cannot be null

* defined in: [product](product-properties-quantity.md "https://examples.com/product.schema.json#/properties/quantity")

### quantity Type

`number`

### quantity Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### quantity Examples

```json
"3"
```

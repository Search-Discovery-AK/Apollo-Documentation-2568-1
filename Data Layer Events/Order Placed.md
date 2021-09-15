# Order Placed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Order Placed",
    "currency": "<currency>",
    "items": [
        {
            "coupon": "<coupon>",
            "discount": "<discount>",
            "item_brand": "<item_brand>",
            "item_id": "<item_id>",
            "item_name": "<item_name>",
            "item_variant": "<item_variant>"
        }
    ],
    "shipping": "<shipping>",
    "tax": "<tax>",
    "transaction_id": "<transaction_id>",
    "value": "<value>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_variant|string|The variant of the item.|Black|||||||
|shipping|number|Shipping cost associated with a transaction.|3.33|||||||
|tax|number|Tax cost associated with a transaction.|1.11|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|||||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||

## Attached Notes

<p>12</p>
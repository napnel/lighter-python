# OrderBookDepthWithBeginNonce


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asks** | [**List[PriceLevel]**](PriceLevel.md) |  | 
**bids** | [**List[PriceLevel]**](PriceLevel.md) |  | 
**offset** | **int** |  | 
**nonce** | **int** |  | 
**begin_nonce** | **int** |  | 

## Example

```python
from lighter.models.order_book_depth_with_begin_nonce import OrderBookDepthWithBeginNonce

# TODO update the JSON string below
json = "{}"
# create an instance of OrderBookDepthWithBeginNonce from a JSON string
order_book_depth_with_begin_nonce_instance = OrderBookDepthWithBeginNonce.from_json(json)
# print the JSON string representation of the object
print(OrderBookDepthWithBeginNonce.to_json())

# convert the object into a dict
order_book_depth_with_begin_nonce_dict = order_book_depth_with_begin_nonce_instance.to_dict()
# create an instance of OrderBookDepthWithBeginNonce from a dict
order_book_depth_with_begin_nonce_from_dict = OrderBookDepthWithBeginNonce.from_dict(order_book_depth_with_begin_nonce_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



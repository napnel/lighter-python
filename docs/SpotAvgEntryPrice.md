# SpotAvgEntryPrice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asset_id** | **int** |  | 
**avg_entry_price** | **str** |  | 
**asset_size** | **str** |  | 
**last_trade_id** | **int** |  | 

## Example

```python
from lighter.models.spot_avg_entry_price import SpotAvgEntryPrice

# TODO update the JSON string below
json = "{}"
# create an instance of SpotAvgEntryPrice from a JSON string
spot_avg_entry_price_instance = SpotAvgEntryPrice.from_json(json)
# print the JSON string representation of the object
print(SpotAvgEntryPrice.to_json())

# convert the object into a dict
spot_avg_entry_price_dict = spot_avg_entry_price_instance.to_dict()
# create an instance of SpotAvgEntryPrice from a dict
spot_avg_entry_price_from_dict = SpotAvgEntryPrice.from_dict(spot_avg_entry_price_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



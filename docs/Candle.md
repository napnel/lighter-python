# Candle


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**t** | **int** |  timestamp | 
**o** | **float** |  open | 
**h** | **float** |  high | 
**l** | **float** |  low | 
**c** | **float** |  close | 
**o** | **float** |  open_raw | 
**h** | **float** |  high_raw | 
**l** | **float** |  low_raw | 
**c** | **float** |  close_raw | 
**v** | **float** |  volume0 | 
**v** | **float** |  volume1 | 
**i** | **int** |  last_trade_id | 

## Example

```python
from lighter.models.candle import Candle

# TODO update the JSON string below
json = "{}"
# create an instance of Candle from a JSON string
candle_instance = Candle.from_json(json)
# print the JSON string representation of the object
print(Candle.to_json())

# convert the object into a dict
candle_dict = candle_instance.to_dict()
# create an instance of Candle from a dict
candle_from_dict = Candle.from_dict(candle_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



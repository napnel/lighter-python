# ReqGetCandles


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**market_id** | **int** |  | 
**resolution** | **str** |  | 
**start_timestamp** | **int** |  | 
**end_timestamp** | **int** |  | 
**count_back** | **int** |  | 
**set_timestamp_to_end** | **bool** |  | [optional] [default to False]

## Example

```python
from lighter.models.req_get_candles import ReqGetCandles

# TODO update the JSON string below
json = "{}"
# create an instance of ReqGetCandles from a JSON string
req_get_candles_instance = ReqGetCandles.from_json(json)
# print the JSON string representation of the object
print(ReqGetCandles.to_json())

# convert the object into a dict
req_get_candles_dict = req_get_candles_instance.to_dict()
# create an instance of ReqGetCandles from a dict
req_get_candles_from_dict = ReqGetCandles.from_dict(req_get_candles_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ReqGetExchangeMetrics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**period** | **str** |  | 
**kind** | **str** |  | 
**filter** | **str** |  | [optional] 
**value** | **str** |  | [optional] 

## Example

```python
from lighter.models.req_get_exchange_metrics import ReqGetExchangeMetrics

# TODO update the JSON string below
json = "{}"
# create an instance of ReqGetExchangeMetrics from a JSON string
req_get_exchange_metrics_instance = ReqGetExchangeMetrics.from_json(json)
# print the JSON string representation of the object
print(ReqGetExchangeMetrics.to_json())

# convert the object into a dict
req_get_exchange_metrics_dict = req_get_exchange_metrics_instance.to_dict()
# create an instance of ReqGetExchangeMetrics from a dict
req_get_exchange_metrics_from_dict = ReqGetExchangeMetrics.from_dict(req_get_exchange_metrics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



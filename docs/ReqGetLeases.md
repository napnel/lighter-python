# ReqGetLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **str** |  made optional to support header auth clients | [optional] 
**account_index** | **int** |  | 
**cursor** | **str** |  | [optional] 
**limit** | **int** |  | [optional] [default to 20]

## Example

```python
from lighter.models.req_get_leases import ReqGetLeases

# TODO update the JSON string below
json = "{}"
# create an instance of ReqGetLeases from a JSON string
req_get_leases_instance = ReqGetLeases.from_json(json)
# print the JSON string representation of the object
print(ReqGetLeases.to_json())

# convert the object into a dict
req_get_leases_dict = req_get_leases_instance.to_dict()
# create an instance of ReqGetLeases from a dict
req_get_leases_from_dict = ReqGetLeases.from_dict(req_get_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



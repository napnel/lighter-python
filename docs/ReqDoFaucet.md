# ReqDoFaucet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**l1_address** | **str** |  | 
**do_l1_transfer** | **bool** |  | [default to False]

## Example

```python
from lighter.models.req_do_faucet import ReqDoFaucet

# TODO update the JSON string below
json = "{}"
# create an instance of ReqDoFaucet from a JSON string
req_do_faucet_instance = ReqDoFaucet.from_json(json)
# print the JSON string representation of the object
print(ReqDoFaucet.to_json())

# convert the object into a dict
req_do_faucet_dict = req_do_faucet_instance.to_dict()
# create an instance of ReqDoFaucet from a dict
req_do_faucet_from_dict = ReqDoFaucet.from_dict(req_do_faucet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



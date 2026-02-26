# ReqGetUserReferrals


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **str** |  | [optional] 
**l1_address** | **str** |  | 
**cursor** | **str** |  | [optional] 

## Example

```python
from lighter.models.req_get_user_referrals import ReqGetUserReferrals

# TODO update the JSON string below
json = "{}"
# create an instance of ReqGetUserReferrals from a JSON string
req_get_user_referrals_instance = ReqGetUserReferrals.from_json(json)
# print the JSON string representation of the object
print(ReqGetUserReferrals.to_json())

# convert the object into a dict
req_get_user_referrals_dict = req_get_user_referrals_instance.to_dict()
# create an instance of ReqGetUserReferrals from a dict
req_get_user_referrals_from_dict = ReqGetUserReferrals.from_dict(req_get_user_referrals_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



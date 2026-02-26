# ReqGetPushNotifSettings


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | **str** |  made optional to support header auth clients | [optional] 
**account_index** | **int** |  | 
**expo_token** | **str** |  | 

## Example

```python
from lighter.models.req_get_push_notif_settings import ReqGetPushNotifSettings

# TODO update the JSON string below
json = "{}"
# create an instance of ReqGetPushNotifSettings from a JSON string
req_get_push_notif_settings_instance = ReqGetPushNotifSettings.from_json(json)
# print the JSON string representation of the object
print(ReqGetPushNotifSettings.to_json())

# convert the object into a dict
req_get_push_notif_settings_dict = req_get_push_notif_settings_instance.to_dict()
# create an instance of ReqGetPushNotifSettings from a dict
req_get_push_notif_settings_from_dict = ReqGetPushNotifSettings.from_dict(req_get_push_notif_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



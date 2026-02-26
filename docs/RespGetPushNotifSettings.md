# RespGetPushNotifSettings


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** |  | 
**message** | **str** |  | [optional] 
**account_index** | **int** |  | 
**enabled** | **bool** |  | 

## Example

```python
from lighter.models.resp_get_push_notif_settings import RespGetPushNotifSettings

# TODO update the JSON string below
json = "{}"
# create an instance of RespGetPushNotifSettings from a JSON string
resp_get_push_notif_settings_instance = RespGetPushNotifSettings.from_json(json)
# print the JSON string representation of the object
print(RespGetPushNotifSettings.to_json())

# convert the object into a dict
resp_get_push_notif_settings_dict = resp_get_push_notif_settings_instance.to_dict()
# create an instance of RespGetPushNotifSettings from a dict
resp_get_push_notif_settings_from_dict = RespGetPushNotifSettings.from_dict(resp_get_push_notif_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



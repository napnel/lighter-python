# PushNotifDeliveryResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expo_token** | **str** |  | 
**status** | **str** |  | 
**error** | **str** |  | 

## Example

```python
from lighter.models.push_notif_delivery_result import PushNotifDeliveryResult

# TODO update the JSON string below
json = "{}"
# create an instance of PushNotifDeliveryResult from a JSON string
push_notif_delivery_result_instance = PushNotifDeliveryResult.from_json(json)
# print the JSON string representation of the object
print(PushNotifDeliveryResult.to_json())

# convert the object into a dict
push_notif_delivery_result_dict = push_notif_delivery_result_instance.to_dict()
# create an instance of PushNotifDeliveryResult from a dict
push_notif_delivery_result_from_dict = PushNotifDeliveryResult.from_dict(push_notif_delivery_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# lighter.ReferralApi

All URIs are relative to *https://mainnet.zklighter.elliot.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**referral_user_referrals**](ReferralApi.md#referral_user_referrals) | **GET** /api/v1/referral/userReferrals | referral_userReferrals


# **referral_user_referrals**
> UserReferrals referral_user_referrals(l1_address, authorization=authorization, auth=auth, cursor=cursor)

referral_userReferrals

Get user referrals

### Example


```python
import lighter
from lighter.models.user_referrals import UserReferrals
from lighter.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://mainnet.zklighter.elliot.ai
# See configuration.py for a list of all supported configuration parameters.
configuration = lighter.Configuration(
    host = "https://mainnet.zklighter.elliot.ai"
)


# Enter a context with an instance of the API client
async with lighter.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = lighter.ReferralApi(api_client)
    l1_address = 'l1_address_example' # str | 
    authorization = 'authorization_example' # str |  (optional)
    auth = 'auth_example' # str |  (optional)
    cursor = 'cursor_example' # str |  (optional)

    try:
        # referral_userReferrals
        api_response = await api_instance.referral_user_referrals(l1_address, authorization=authorization, auth=auth, cursor=cursor)
        print("The response of ReferralApi->referral_user_referrals:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ReferralApi->referral_user_referrals: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **l1_address** | **str**|  | 
 **authorization** | **str**|  | [optional] 
 **auth** | **str**|  | [optional] 
 **cursor** | **str**|  | [optional] 

### Return type

[**UserReferrals**](UserReferrals.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A successful response. |  -  |
**400** | Bad request |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# lighter.PushnotifApi

All URIs are relative to *https://mainnet.zklighter.elliot.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_pushnotif_settings**](PushnotifApi.md#get_pushnotif_settings) | **GET** /api/v1/pushnotif/settings | get_pushnotif_settings
[**post_pushnotif_settings**](PushnotifApi.md#post_pushnotif_settings) | **POST** /api/v1/pushnotif/settings | post_pushnotif_settings
[**pushnotif_register**](PushnotifApi.md#pushnotif_register) | **POST** /api/v1/pushnotif/register | pushnotif_register
[**pushnotif_unregister**](PushnotifApi.md#pushnotif_unregister) | **POST** /api/v1/pushnotif/unregister | pushnotif_unregister


# **get_pushnotif_settings**
> RespGetPushNotifSettings get_pushnotif_settings(account_index, expo_token, authorization=authorization, auth=auth)

get_pushnotif_settings

Get push notification settings

### Example


```python
import lighter
from lighter.models.resp_get_push_notif_settings import RespGetPushNotifSettings
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
    api_instance = lighter.PushnotifApi(api_client)
    account_index = 56 # int | 
    expo_token = 'expo_token_example' # str | 
    authorization = 'authorization_example' # str |  make required after integ is done (optional)
    auth = 'auth_example' # str |  made optional to support header auth clients (optional)

    try:
        # get_pushnotif_settings
        api_response = await api_instance.get_pushnotif_settings(account_index, expo_token, authorization=authorization, auth=auth)
        print("The response of PushnotifApi->get_pushnotif_settings:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PushnotifApi->get_pushnotif_settings: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_index** | **int**|  | 
 **expo_token** | **str**|  | 
 **authorization** | **str**|  make required after integ is done | [optional] 
 **auth** | **str**|  made optional to support header auth clients | [optional] 

### Return type

[**RespGetPushNotifSettings**](RespGetPushNotifSettings.md)

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

# **post_pushnotif_settings**
> ResultCode post_pushnotif_settings(account_index, expo_token, enabled, auth=auth)

post_pushnotif_settings

Update push notification settings

### Example


```python
import lighter
from lighter.models.result_code import ResultCode
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
    api_instance = lighter.PushnotifApi(api_client)
    account_index = 56 # int | 
    expo_token = 'expo_token_example' # str | 
    enabled = True # bool | 
    auth = 'auth_example' # str |  made optional to support header auth clients (optional)

    try:
        # post_pushnotif_settings
        api_response = await api_instance.post_pushnotif_settings(account_index, expo_token, enabled, auth=auth)
        print("The response of PushnotifApi->post_pushnotif_settings:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PushnotifApi->post_pushnotif_settings: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_index** | **int**|  | 
 **expo_token** | **str**|  | 
 **enabled** | **bool**|  | 
 **auth** | **str**|  made optional to support header auth clients | [optional] 

### Return type

[**ResultCode**](ResultCode.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A successful response. |  -  |
**400** | Bad request |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pushnotif_register**
> ResultCode pushnotif_register(account_index, expo_token, platform, auth=auth, app_version=app_version)

pushnotif_register

Register device for push notifications

### Example


```python
import lighter
from lighter.models.result_code import ResultCode
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
    api_instance = lighter.PushnotifApi(api_client)
    account_index = 56 # int | 
    expo_token = 'expo_token_example' # str | 
    platform = 'platform_example' # str | 
    auth = 'auth_example' # str |  made optional to support header auth clients (optional)
    app_version = 'app_version_example' # str |  (optional)

    try:
        # pushnotif_register
        api_response = await api_instance.pushnotif_register(account_index, expo_token, platform, auth=auth, app_version=app_version)
        print("The response of PushnotifApi->pushnotif_register:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PushnotifApi->pushnotif_register: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_index** | **int**|  | 
 **expo_token** | **str**|  | 
 **platform** | **str**|  | 
 **auth** | **str**|  made optional to support header auth clients | [optional] 
 **app_version** | **str**|  | [optional] 

### Return type

[**ResultCode**](ResultCode.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A successful response. |  -  |
**400** | Bad request |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pushnotif_unregister**
> ResultCode pushnotif_unregister(account_index, expo_token, auth=auth)

pushnotif_unregister

Unregister device from push notifications

### Example


```python
import lighter
from lighter.models.result_code import ResultCode
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
    api_instance = lighter.PushnotifApi(api_client)
    account_index = 56 # int | 
    expo_token = 'expo_token_example' # str | 
    auth = 'auth_example' # str |  made optional to support header auth clients (optional)

    try:
        # pushnotif_unregister
        api_response = await api_instance.pushnotif_unregister(account_index, expo_token, auth=auth)
        print("The response of PushnotifApi->pushnotif_unregister:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PushnotifApi->pushnotif_unregister: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_index** | **int**|  | 
 **expo_token** | **str**|  | 
 **auth** | **str**|  made optional to support header auth clients | [optional] 

### Return type

[**ResultCode**](ResultCode.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A successful response. |  -  |
**400** | Bad request |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


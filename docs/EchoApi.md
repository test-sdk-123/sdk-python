# test-123.EchoApi

All URIs are relative to *https://www/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**echo**](EchoApi.md#echo) | **POST** /echo | Echo test


# **echo**
> str echo(body)

Echo test

Receive the exact message you've sent

### Example

* Api Key Authentication (api_key):

```python
import test-123
from test-123.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://www/api/v1
configuration = test-123.Configuration(
    host = "https://www/api/v1",
    api_key = os.environ["API_KEY"]
)

# Enter a context with an instance of the API client
with test-123.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = test-123.EchoApi(api_client)
    body = 'body_example' # str | Echo payload

    try:
        # Echo test
        api_response = api_instance.echo(body)
        print("The response of EchoApi->echo:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EchoApi->echo: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **str**| Echo payload | 

### Return type

**str**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json, application/xml
 - **Accept**: application/json, application/xml, text/csv

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | OK |  * X-Rate-Limit - calls per hour allowed by the user <br>  * X-Expires-After -  <br>  |
**400** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


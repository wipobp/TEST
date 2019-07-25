# TAGApi

All URIs are relative to *https://www.bankig.com/base*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get10**](TAGApi.md#get10) | **GET** /connect | summary of get


<a name="get10"></a>
# **get10**
> String get10(name)

summary of get

get the user

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TAGApi;


TAGApi apiInstance = new TAGApi();
String name = "name_example"; // String | name of user
try {
    String result = apiInstance.get10(name);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling TAGApi#get10");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **String**| name of user |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: JSON
 - **Accept**: TEXT


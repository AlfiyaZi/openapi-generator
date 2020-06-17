# PSPetstore.PSPetstore/Api.PSDefaultApi

All URIs are relative to *http://petstore.swagger.io:80/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Invoke-PSFooGet**](PSDefaultApi.md#Invoke-PSFooGet) | **GET** /foo | 


<a name="Invoke-PSFooGet"></a>
# **Invoke-PSFooGet**
> InlineResponseDefault Invoke-PSFooGet<br>



### Example
```powershell
Import-Module -Name PSPetstore


try {
    InlineResponseDefault $Result = Invoke-PSFooGet
} catch {
    Write-Host ("Exception occured when calling Invoke-PSFooGet: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponseDefault**](InlineResponseDefault.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

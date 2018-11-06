# IO.Swagger.Api.DefaultApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteArtifact**](DefaultApi.md#deleteartifact) | **DELETE** /artifact/{id} | Deletes an artifact
[**DeleteUser**](DefaultApi.md#deleteuser) | **DELETE** /user/{id} | Deletes an user from the database
[**GetArtifact**](DefaultApi.md#getartifact) | **GET** /artifact/{id} | Gets an artifact
[**GetArtifacts**](DefaultApi.md#getartifacts) | **GET** /artifact/ | Gets all the artifacts
[**GetUserAwards**](DefaultApi.md#getuserawards) | **GET** /user/{id}/awards | Gets the user&#39;s awards
[**GetUserCollectedItems**](DefaultApi.md#getusercollecteditems) | **GET** /user/{id}/collectedItems/ | Gets the user&#39;s collected items
[**GetUserPersonalInfo**](DefaultApi.md#getuserpersonalinfo) | **GET** /user/{id}/personalInfo | Gets the user&#39;s personal information
[**GetUsers**](DefaultApi.md#getusers) | **GET** /user/ | Gets all the users
[**PostArtifacts**](DefaultApi.md#postartifacts) | **POST** /artifact/ | Creates an artifact
[**PostUserLogin**](DefaultApi.md#postuserlogin) | **POST** /user/login | Given an user and password tells if they matches in the database
[**PostUsers**](DefaultApi.md#postusers) | **POST** /user/ | Creates an user
[**PutUserAwards**](DefaultApi.md#putuserawards) | **PUT** /user/{id}/awards | Updates the user&#39;s awards
[**PutUserCollectedItems**](DefaultApi.md#putusercollecteditems) | **PUT** /user/{id}/collectedItems/ | 
[**PutUserPersonalInfo**](DefaultApi.md#putuserpersonalinfo) | **PUT** /user/{id}/personalInfo | Updates the user&#39;s personal information


<a name="deleteartifact"></a>
# **DeleteArtifact**
> void DeleteArtifact (string id)

Deletes an artifact

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class DeleteArtifactExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 

            try
            {
                // Deletes an artifact
                apiInstance.DeleteArtifact(id);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.DeleteArtifact: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="deleteuser"></a>
# **DeleteUser**
> void DeleteUser (string id)

Deletes an user from the database

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class DeleteUserExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 

            try
            {
                // Deletes an user from the database
                apiInstance.DeleteUser(id);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.DeleteUser: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getartifact"></a>
# **GetArtifact**
> void GetArtifact (string id, List<string> fields = null)

Gets an artifact

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetArtifactExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var fields = new List<string>(); // List<string> |  (optional) 

            try
            {
                // Gets an artifact
                apiInstance.GetArtifact(id, fields);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetArtifact: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **fields** | [**List&lt;string&gt;**](string.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getartifacts"></a>
# **GetArtifacts**
> void GetArtifacts ()

Gets all the artifacts

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetArtifactsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();

            try
            {
                // Gets all the artifacts
                apiInstance.GetArtifacts();
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetArtifacts: " + e.Message );
            }
        }
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getuserawards"></a>
# **GetUserAwards**
> void GetUserAwards (string id, List<string> fields = null)

Gets the user's awards

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetUserAwardsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var fields = new List<string>(); // List<string> |  (optional) 

            try
            {
                // Gets the user's awards
                apiInstance.GetUserAwards(id, fields);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetUserAwards: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **fields** | [**List&lt;string&gt;**](string.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getusercollecteditems"></a>
# **GetUserCollectedItems**
> void GetUserCollectedItems (string id, bool? types = null)

Gets the user's collected items

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetUserCollectedItemsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var types = true;  // bool? |  (optional) 

            try
            {
                // Gets the user's collected items
                apiInstance.GetUserCollectedItems(id, types);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetUserCollectedItems: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **types** | **bool?**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getuserpersonalinfo"></a>
# **GetUserPersonalInfo**
> void GetUserPersonalInfo (string id, List<string> fields = null)

Gets the user's personal information

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetUserPersonalInfoExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var fields = new List<string>(); // List<string> |  (optional) 

            try
            {
                // Gets the user's personal information
                apiInstance.GetUserPersonalInfo(id, fields);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetUserPersonalInfo: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **fields** | [**List&lt;string&gt;**](string.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="getusers"></a>
# **GetUsers**
> void GetUsers ()

Gets all the users

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetUsersExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();

            try
            {
                // Gets all the users
                apiInstance.GetUsers();
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetUsers: " + e.Message );
            }
        }
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="postartifacts"></a>
# **PostArtifacts**
> void PostArtifacts (string type, decimal? latitude, decimal? longitude, string path = null)

Creates an artifact

:raises DuplicateKeyError if the artifact already exists.

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PostArtifactsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var type = type_example;  // string | 
            var latitude = 8.14;  // decimal? | 
            var longitude = 8.14;  // decimal? | 
            var path = path_example;  // string |  (optional) 

            try
            {
                // Creates an artifact
                apiInstance.PostArtifacts(type, latitude, longitude, path);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PostArtifacts: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | **string**|  | 
 **latitude** | **decimal?**|  | 
 **longitude** | **decimal?**|  | 
 **path** | **string**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="postuserlogin"></a>
# **PostUserLogin**
> void PostUserLogin (string nickname, string password)

Given an user and password tells if they matches in the database

Returns: The id of the user.

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PostUserLoginExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var nickname = nickname_example;  // string | 
            var password = password_example;  // string | 

            try
            {
                // Given an user and password tells if they matches in the database
                apiInstance.PostUserLogin(nickname, password);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PostUserLogin: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **nickname** | **string**|  | 
 **password** | **string**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="postusers"></a>
# **PostUsers**
> void PostUsers (string nickname, string email, string password, string gender)

Creates an user

:raises DuplicateKeyError if the artifact already exists.

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PostUsersExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var nickname = nickname_example;  // string | 
            var email = email_example;  // string | 
            var password = password_example;  // string | 
            var gender = gender_example;  // string | 

            try
            {
                // Creates an user
                apiInstance.PostUsers(nickname, email, password, gender);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PostUsers: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **nickname** | **string**|  | 
 **email** | **string**|  | 
 **password** | **string**|  | 
 **gender** | **string**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="putuserawards"></a>
# **PutUserAwards**
> void PutUserAwards (string id, int? digQuantity = null, int? gatherQuantity = null, int? searchQuantity = null, bool? increase = null)

Updates the user's awards

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PutUserAwardsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var digQuantity = 56;  // int? |  (optional) 
            var gatherQuantity = 56;  // int? |  (optional) 
            var searchQuantity = 56;  // int? |  (optional) 
            var increase = true;  // bool? | If 'true', then increments rest of fields by the given values (optional) 

            try
            {
                // Updates the user's awards
                apiInstance.PutUserAwards(id, digQuantity, gatherQuantity, searchQuantity, increase);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PutUserAwards: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **digQuantity** | **int?**|  | [optional] 
 **gatherQuantity** | **int?**|  | [optional] 
 **searchQuantity** | **int?**|  | [optional] 
 **increase** | **bool?**| If &#39;true&#39;, then increments rest of fields by the given values | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="putusercollecteditems"></a>
# **PutUserCollectedItems**
> void PutUserCollectedItems (string id, int? value, string artifactId = null, bool? increase = null)



### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PutUserCollectedItemsExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var value = 56;  // int? | 
            var artifactId = artifactId_example;  // string |  (optional) 
            var increase = true;  // bool? |  (optional) 

            try
            {
                apiInstance.PutUserCollectedItems(id, value, artifactId, increase);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PutUserCollectedItems: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **value** | **int?**|  | 
 **artifactId** | **string**|  | [optional] 
 **increase** | **bool?**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a name="putuserpersonalinfo"></a>
# **PutUserPersonalInfo**
> void PutUserPersonalInfo (string id, bool? active = null, string email = null, string gender = null, string isTutorialDone = null, int? level = null, int? experience = null, string nickname = null)

Updates the user's personal information

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class PutUserPersonalInfoExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();
            var id = id_example;  // string | 
            var active = true;  // bool? |  (optional) 
            var email = email_example;  // string |  (optional) 
            var gender = gender_example;  // string |  (optional) 
            var isTutorialDone = isTutorialDone_example;  // string |  (optional) 
            var level = 56;  // int? |  (optional) 
            var experience = 56;  // int? |  (optional) 
            var nickname = nickname_example;  // string |  (optional) 

            try
            {
                // Updates the user's personal information
                apiInstance.PutUserPersonalInfo(id, active, email, gender, isTutorialDone, level, experience, nickname);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.PutUserPersonalInfo: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  | 
 **active** | **bool?**|  | [optional] 
 **email** | **string**|  | [optional] 
 **gender** | **string**|  | [optional] 
 **isTutorialDone** | **string**|  | [optional] 
 **level** | **int?**|  | [optional] 
 **experience** | **int?**|  | [optional] 
 **nickname** | **string**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


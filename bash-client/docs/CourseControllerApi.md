# CourseControllerApi

All URIs are relative to **

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCourseByIdUsingDELETE**](CourseControllerApi.md#deleteCourseByIdUsingDELETE) | **DELETE** /courses/courses/{courseid} | deletes Course by Id
[**getCountStudentsInCoursesUsingGET**](CourseControllerApi.md#getCountStudentsInCoursesUsingGET) | **GET** /courses/studcount | returns Student Count in Courses
[**listAllCoursesUsingGET**](CourseControllerApi.md#listAllCoursesUsingGET) | **GET** /courses/courses | returns all Courses


## **deleteCourseByIdUsingDELETE**

deletes Course by Id

### Example
```bash
 deleteCourseByIdUsingDELETE courseid=value
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **courseid** | **integer** | courseid |

### Return type

[**Course**](Course.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **getCountStudentsInCoursesUsingGET**

returns Student Count in Courses

### Example
```bash
 getCountStudentsInCoursesUsingGET
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Course**](Course.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **listAllCoursesUsingGET**

returns all Courses

### Example
```bash
 listAllCoursesUsingGET  page=value  size=value  Specify as:  sort=value1 sort=value2 sort=...
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | [**Object**](.md) | Results page you want to retrieve (0..N) | [optional]
 **size** | [**Object**](.md) | Number of records per page. | [optional]
 **sort** | [**array[string]**](string.md) | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | [optional]

### Return type

[**array[Course]**](Course.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


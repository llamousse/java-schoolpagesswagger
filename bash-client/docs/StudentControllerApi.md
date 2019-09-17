# StudentControllerApi

All URIs are relative to **

Method | HTTP request | Description
------------- | ------------- | -------------
[**addNewStudentUsingPOST**](StudentControllerApi.md#addNewStudentUsingPOST) | **POST** /students/Student | Creates a new Student
[**deleteStudentByIdUsingDELETE**](StudentControllerApi.md#deleteStudentByIdUsingDELETE) | **DELETE** /students/Student/{Studentid} | deletes Student by Id
[**getStudentByIdUsingGET**](StudentControllerApi.md#getStudentByIdUsingGET) | **GET** /students/Student/{StudentId} | returns Student by Id
[**getStudentByNameContainingUsingGET**](StudentControllerApi.md#getStudentByNameContainingUsingGET) | **GET** /students/student/namelike/{name} | returns Student by Name
[**listAllStudentsUsingGET**](StudentControllerApi.md#listAllStudentsUsingGET) | **GET** /students/students | returns all Students
[**updateStudentUsingPUT**](StudentControllerApi.md#updateStudentUsingPUT) | **PUT** /students/Student/{Studentid} | Updates a Student


## **addNewStudentUsingPOST**

Creates a new Student

The newly created student id will be sent in the location header

### Example
```bash
 addNewStudentUsingPOST
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **newStudent** | [**Student**](Student.md) | newStudent |

### Return type

**map**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **deleteStudentByIdUsingDELETE**

deletes Student by Id

### Example
```bash
 deleteStudentByIdUsingDELETE Studentid=value
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **studentid** | **integer** | Studentid |

### Return type

[**Student**](Student.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **getStudentByIdUsingGET**

returns Student by Id

### Example
```bash
 getStudentByIdUsingGET StudentId=value
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **studentId** | **integer** | StudentId |

### Return type

[**Student**](Student.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **getStudentByNameContainingUsingGET**

returns Student by Name

### Example
```bash
 getStudentByNameContainingUsingGET name=value
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | name |

### Return type

[**Student**](Student.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **listAllStudentsUsingGET**

returns all Students

### Example
```bash
 listAllStudentsUsingGET  page=value  size=value  Specify as:  sort=value1 sort=value2 sort=...
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | [**Object**](.md) | Results page you want to retrieve (0..N) | [optional]
 **size** | [**Object**](.md) | Number of records per page. | [optional]
 **sort** | [**array[string]**](string.md) | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | [optional]

### Return type

[**array[Student]**](Student.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not Applicable
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## **updateStudentUsingPUT**

Updates a Student

### Example
```bash
 updateStudentUsingPUT Studentid=value
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **studentid** | **integer** | Studentid |
 **updateStudent** | [**Student**](Student.md) | updateStudent |

### Return type

[**Student**](Student.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


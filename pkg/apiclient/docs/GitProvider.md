# GitProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseApiUrl** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**Token** | **string** |  | 
**Username** | **string** |  | 

## Methods

### NewGitProvider

`func NewGitProvider(id string, token string, username string, ) *GitProvider`

NewGitProvider instantiates a new GitProvider object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGitProviderWithDefaults

`func NewGitProviderWithDefaults() *GitProvider`

NewGitProviderWithDefaults instantiates a new GitProvider object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseApiUrl

`func (o *GitProvider) GetBaseApiUrl() string`

GetBaseApiUrl returns the BaseApiUrl field if non-nil, zero value otherwise.

### GetBaseApiUrlOk

`func (o *GitProvider) GetBaseApiUrlOk() (*string, bool)`

GetBaseApiUrlOk returns a tuple with the BaseApiUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseApiUrl

`func (o *GitProvider) SetBaseApiUrl(v string)`

SetBaseApiUrl sets BaseApiUrl field to given value.

### HasBaseApiUrl

`func (o *GitProvider) HasBaseApiUrl() bool`

HasBaseApiUrl returns a boolean if a field has been set.

### GetId

`func (o *GitProvider) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GitProvider) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GitProvider) SetId(v string)`

SetId sets Id field to given value.


### GetToken

`func (o *GitProvider) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *GitProvider) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *GitProvider) SetToken(v string)`

SetToken sets Token field to given value.


### GetUsername

`func (o *GitProvider) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *GitProvider) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *GitProvider) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



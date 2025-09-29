# SubmitSingleDocWithTemplateParamsRequestOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobTemplate** | **string** |  | 
**PaymentDetails** | Pointer to [**PaymentDetails**](PaymentDetails.md) |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**DocumentSourceIdentifier** | [**DocumentSourceIdentifier**](DocumentSourceIdentifier.md) |  | 

## Methods

### NewSubmitSingleDocWithTemplateParamsRequestOneOf

`func NewSubmitSingleDocWithTemplateParamsRequestOneOf(jobTemplate string, documentSourceIdentifier DocumentSourceIdentifier, ) *SubmitSingleDocWithTemplateParamsRequestOneOf`

NewSubmitSingleDocWithTemplateParamsRequestOneOf instantiates a new SubmitSingleDocWithTemplateParamsRequestOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitSingleDocWithTemplateParamsRequestOneOfWithDefaults

`func NewSubmitSingleDocWithTemplateParamsRequestOneOfWithDefaults() *SubmitSingleDocWithTemplateParamsRequestOneOf`

NewSubmitSingleDocWithTemplateParamsRequestOneOfWithDefaults instantiates a new SubmitSingleDocWithTemplateParamsRequestOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobTemplate

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetJobTemplate() string`

GetJobTemplate returns the JobTemplate field if non-nil, zero value otherwise.

### GetJobTemplateOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetJobTemplateOk() (*string, bool)`

GetJobTemplateOk returns a tuple with the JobTemplate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTemplate

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) SetJobTemplate(v string)`

SetJobTemplate sets JobTemplate field to given value.


### GetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetPaymentDetails() PaymentDetails`

GetPaymentDetails returns the PaymentDetails field if non-nil, zero value otherwise.

### GetPaymentDetailsOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetPaymentDetailsOk() (*PaymentDetails, bool)`

GetPaymentDetailsOk returns a tuple with the PaymentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) SetPaymentDetails(v PaymentDetails)`

SetPaymentDetails sets PaymentDetails field to given value.

### HasPaymentDetails

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) HasPaymentDetails() bool`

HasPaymentDetails returns a boolean if a field has been set.

### GetTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDocumentSourceIdentifier

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetDocumentSourceIdentifier() DocumentSourceIdentifier`

GetDocumentSourceIdentifier returns the DocumentSourceIdentifier field if non-nil, zero value otherwise.

### GetDocumentSourceIdentifierOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) GetDocumentSourceIdentifierOk() (*DocumentSourceIdentifier, bool)`

GetDocumentSourceIdentifierOk returns a tuple with the DocumentSourceIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentSourceIdentifier

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf) SetDocumentSourceIdentifier(v DocumentSourceIdentifier)`

SetDocumentSourceIdentifier sets DocumentSourceIdentifier field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SubmitSingleDocWithTemplateParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobTemplate** | **string** |  | 
**PaymentDetails** | Pointer to [**PaymentDetails**](PaymentDetails.md) |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**DocumentSourceIdentifier** | [**DocumentSourceIdentifier**](DocumentSourceIdentifier.md) |  | 
**RecipientAddressSources** | [**[]RecipientAddressSource**](RecipientAddressSource.md) |  | 

## Methods

### NewSubmitSingleDocWithTemplateParams

`func NewSubmitSingleDocWithTemplateParams(jobTemplate string, documentSourceIdentifier DocumentSourceIdentifier, recipientAddressSources []RecipientAddressSource, ) *SubmitSingleDocWithTemplateParams`

NewSubmitSingleDocWithTemplateParams instantiates a new SubmitSingleDocWithTemplateParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitSingleDocWithTemplateParamsWithDefaults

`func NewSubmitSingleDocWithTemplateParamsWithDefaults() *SubmitSingleDocWithTemplateParams`

NewSubmitSingleDocWithTemplateParamsWithDefaults instantiates a new SubmitSingleDocWithTemplateParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobTemplate

`func (o *SubmitSingleDocWithTemplateParams) GetJobTemplate() string`

GetJobTemplate returns the JobTemplate field if non-nil, zero value otherwise.

### GetJobTemplateOk

`func (o *SubmitSingleDocWithTemplateParams) GetJobTemplateOk() (*string, bool)`

GetJobTemplateOk returns a tuple with the JobTemplate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTemplate

`func (o *SubmitSingleDocWithTemplateParams) SetJobTemplate(v string)`

SetJobTemplate sets JobTemplate field to given value.


### GetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParams) GetPaymentDetails() PaymentDetails`

GetPaymentDetails returns the PaymentDetails field if non-nil, zero value otherwise.

### GetPaymentDetailsOk

`func (o *SubmitSingleDocWithTemplateParams) GetPaymentDetailsOk() (*PaymentDetails, bool)`

GetPaymentDetailsOk returns a tuple with the PaymentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParams) SetPaymentDetails(v PaymentDetails)`

SetPaymentDetails sets PaymentDetails field to given value.

### HasPaymentDetails

`func (o *SubmitSingleDocWithTemplateParams) HasPaymentDetails() bool`

HasPaymentDetails returns a boolean if a field has been set.

### GetTags

`func (o *SubmitSingleDocWithTemplateParams) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *SubmitSingleDocWithTemplateParams) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *SubmitSingleDocWithTemplateParams) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *SubmitSingleDocWithTemplateParams) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDocumentSourceIdentifier

`func (o *SubmitSingleDocWithTemplateParams) GetDocumentSourceIdentifier() DocumentSourceIdentifier`

GetDocumentSourceIdentifier returns the DocumentSourceIdentifier field if non-nil, zero value otherwise.

### GetDocumentSourceIdentifierOk

`func (o *SubmitSingleDocWithTemplateParams) GetDocumentSourceIdentifierOk() (*DocumentSourceIdentifier, bool)`

GetDocumentSourceIdentifierOk returns a tuple with the DocumentSourceIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentSourceIdentifier

`func (o *SubmitSingleDocWithTemplateParams) SetDocumentSourceIdentifier(v DocumentSourceIdentifier)`

SetDocumentSourceIdentifier sets DocumentSourceIdentifier field to given value.


### GetRecipientAddressSources

`func (o *SubmitSingleDocWithTemplateParams) GetRecipientAddressSources() []RecipientAddressSource`

GetRecipientAddressSources returns the RecipientAddressSources field if non-nil, zero value otherwise.

### GetRecipientAddressSourcesOk

`func (o *SubmitSingleDocWithTemplateParams) GetRecipientAddressSourcesOk() (*[]RecipientAddressSource, bool)`

GetRecipientAddressSourcesOk returns a tuple with the RecipientAddressSources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientAddressSources

`func (o *SubmitSingleDocWithTemplateParams) SetRecipientAddressSources(v []RecipientAddressSource)`

SetRecipientAddressSources sets RecipientAddressSources field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



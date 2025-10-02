# SubmitSingleDocWithTemplateParamsRequestOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobTemplate** | **string** |  | 
**PaymentDetails** | [**PaymentDetails**](PaymentDetails.md) |  | 
**Tags** | Pointer to **[]string** |  | [optional] 
**RecipientAddressSources** | [**[]RecipientAddressSource**](RecipientAddressSource.md) |  | 

## Methods

### NewSubmitSingleDocWithTemplateParamsRequestOneOf1

`func NewSubmitSingleDocWithTemplateParamsRequestOneOf1(jobTemplate string, paymentDetails PaymentDetails, recipientAddressSources []RecipientAddressSource, ) *SubmitSingleDocWithTemplateParamsRequestOneOf1`

NewSubmitSingleDocWithTemplateParamsRequestOneOf1 instantiates a new SubmitSingleDocWithTemplateParamsRequestOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitSingleDocWithTemplateParamsRequestOneOf1WithDefaults

`func NewSubmitSingleDocWithTemplateParamsRequestOneOf1WithDefaults() *SubmitSingleDocWithTemplateParamsRequestOneOf1`

NewSubmitSingleDocWithTemplateParamsRequestOneOf1WithDefaults instantiates a new SubmitSingleDocWithTemplateParamsRequestOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobTemplate

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetJobTemplate() string`

GetJobTemplate returns the JobTemplate field if non-nil, zero value otherwise.

### GetJobTemplateOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetJobTemplateOk() (*string, bool)`

GetJobTemplateOk returns a tuple with the JobTemplate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTemplate

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) SetJobTemplate(v string)`

SetJobTemplate sets JobTemplate field to given value.


### GetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetPaymentDetails() PaymentDetails`

GetPaymentDetails returns the PaymentDetails field if non-nil, zero value otherwise.

### GetPaymentDetailsOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetPaymentDetailsOk() (*PaymentDetails, bool)`

GetPaymentDetailsOk returns a tuple with the PaymentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDetails

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) SetPaymentDetails(v PaymentDetails)`

SetPaymentDetails sets PaymentDetails field to given value.


### GetTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetRecipientAddressSources

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetRecipientAddressSources() []RecipientAddressSource`

GetRecipientAddressSources returns the RecipientAddressSources field if non-nil, zero value otherwise.

### GetRecipientAddressSourcesOk

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) GetRecipientAddressSourcesOk() (*[]RecipientAddressSource, bool)`

GetRecipientAddressSourcesOk returns a tuple with the RecipientAddressSources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientAddressSources

`func (o *SubmitSingleDocWithTemplateParamsRequestOneOf1) SetRecipientAddressSources(v []RecipientAddressSource)`

SetRecipientAddressSources sets RecipientAddressSources field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



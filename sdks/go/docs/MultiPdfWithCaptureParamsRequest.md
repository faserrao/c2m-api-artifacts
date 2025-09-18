# MultiPdfWithCaptureParamsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressCapturePdfs** | [**[]AddressListPdf**](AddressListPdf.md) |  | 
**PaymentDetails** | [**PaymentDetails**](PaymentDetails.md) |  | 
**Tags** | Pointer to **[]string** |  | [optional] 

## Methods

### NewMultiPdfWithCaptureParamsRequest

`func NewMultiPdfWithCaptureParamsRequest(addressCapturePdfs []AddressListPdf, paymentDetails PaymentDetails, ) *MultiPdfWithCaptureParamsRequest`

NewMultiPdfWithCaptureParamsRequest instantiates a new MultiPdfWithCaptureParamsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMultiPdfWithCaptureParamsRequestWithDefaults

`func NewMultiPdfWithCaptureParamsRequestWithDefaults() *MultiPdfWithCaptureParamsRequest`

NewMultiPdfWithCaptureParamsRequestWithDefaults instantiates a new MultiPdfWithCaptureParamsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressCapturePdfs

`func (o *MultiPdfWithCaptureParamsRequest) GetAddressCapturePdfs() []AddressListPdf`

GetAddressCapturePdfs returns the AddressCapturePdfs field if non-nil, zero value otherwise.

### GetAddressCapturePdfsOk

`func (o *MultiPdfWithCaptureParamsRequest) GetAddressCapturePdfsOk() (*[]AddressListPdf, bool)`

GetAddressCapturePdfsOk returns a tuple with the AddressCapturePdfs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCapturePdfs

`func (o *MultiPdfWithCaptureParamsRequest) SetAddressCapturePdfs(v []AddressListPdf)`

SetAddressCapturePdfs sets AddressCapturePdfs field to given value.


### GetPaymentDetails

`func (o *MultiPdfWithCaptureParamsRequest) GetPaymentDetails() PaymentDetails`

GetPaymentDetails returns the PaymentDetails field if non-nil, zero value otherwise.

### GetPaymentDetailsOk

`func (o *MultiPdfWithCaptureParamsRequest) GetPaymentDetailsOk() (*PaymentDetails, bool)`

GetPaymentDetailsOk returns a tuple with the PaymentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDetails

`func (o *MultiPdfWithCaptureParamsRequest) SetPaymentDetails(v PaymentDetails)`

SetPaymentDetails sets PaymentDetails field to given value.


### GetTags

`func (o *MultiPdfWithCaptureParamsRequest) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *MultiPdfWithCaptureParamsRequest) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *MultiPdfWithCaptureParamsRequest) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *MultiPdfWithCaptureParamsRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



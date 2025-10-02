# SubmitSingleDocWithTemplateParamsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**jobTemplate** | **string** |  | [default to undefined]
**paymentDetails** | [**PaymentDetails**](PaymentDetails.md) |  | [default to undefined]
**tags** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**documentSourceIdentifier** | [**DocumentSourceIdentifier**](DocumentSourceIdentifier.md) |  | [default to undefined]
**recipientAddressSources** | [**Array&lt;RecipientAddressSource&gt;**](RecipientAddressSource.md) |  | [default to undefined]

## Example

```typescript
import { SubmitSingleDocWithTemplateParamsRequest } from './api';

const instance: SubmitSingleDocWithTemplateParamsRequest = {
    jobTemplate,
    paymentDetails,
    tags,
    documentSourceIdentifier,
    recipientAddressSources,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

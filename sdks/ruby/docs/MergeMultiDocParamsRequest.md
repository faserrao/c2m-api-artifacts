# OpenapiClient::MergeMultiDocParamsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **documents_to_merge** | [**Array&lt;DocumentSourceIdentifier&gt;**](DocumentSourceIdentifier.md) |  |  |
| **recipient_address_source** | [**RecipientAddressSource**](RecipientAddressSource.md) |  |  |
| **payment_details** | [**PaymentDetails**](PaymentDetails.md) |  |  |
| **tags** | **Array&lt;String&gt;** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::MergeMultiDocParamsRequest.new(
  documents_to_merge: null,
  recipient_address_source: null,
  payment_details: null,
  tags: null
)
```


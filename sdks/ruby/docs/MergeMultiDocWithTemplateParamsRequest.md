# OpenapiClient::MergeMultiDocWithTemplateParamsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **documents_to_merge** | [**Array&lt;DocumentSourceIdentifier&gt;**](DocumentSourceIdentifier.md) |  |  |
| **job_template** | **String** |  |  |
| **payment_details** | [**PaymentDetails**](PaymentDetails.md) |  |  |
| **tags** | **Array&lt;String&gt;** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::MergeMultiDocWithTemplateParamsRequest.new(
  documents_to_merge: null,
  job_template: null,
  payment_details: null,
  tags: null
)
```


# OpenapiClient::SubmitSingleDocWithTemplateParamsRequestOneOf

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **job_template** | **String** |  |  |
| **payment_details** | [**PaymentDetails**](PaymentDetails.md) |  |  |
| **tags** | **Array&lt;String&gt;** |  | [optional] |
| **document_source_identifier** | [**DocumentSourceIdentifier**](DocumentSourceIdentifier.md) |  |  |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::SubmitSingleDocWithTemplateParamsRequestOneOf.new(
  job_template: null,
  payment_details: null,
  tags: null,
  document_source_identifier: null
)
```


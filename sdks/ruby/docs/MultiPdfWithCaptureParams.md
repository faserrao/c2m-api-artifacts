# OpenapiClient::MultiPdfWithCaptureParams

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **address_capture_pdfs** | [**Array&lt;AddressListPdf&gt;**](AddressListPdf.md) |  |  |
| **payment_details** | [**PaymentDetails**](PaymentDetails.md) |  |  |
| **tags** | **Array&lt;String&gt;** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::MultiPdfWithCaptureParams.new(
  address_capture_pdfs: null,
  payment_details: null,
  tags: null
)
```


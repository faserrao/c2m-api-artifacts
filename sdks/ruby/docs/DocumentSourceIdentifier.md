# OpenapiClient::DocumentSourceIdentifier

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'openapi_client'

OpenapiClient::DocumentSourceIdentifier.openapi_one_of
# =>
# [
#   :'DocumentSourceFromZip',
#   :'DocumentSourceVariant1',
#   :'DocumentSourceVariant2',
#   :'DocumentSourceWithUpload',
#   :'DocumentSourceWithUploadAndZip'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'openapi_client'

OpenapiClient::DocumentSourceIdentifier.build(data)
# => #<DocumentSourceFromZip:0x00007fdd4aab02a0>

OpenapiClient::DocumentSourceIdentifier.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `DocumentSourceFromZip`
- `DocumentSourceVariant1`
- `DocumentSourceVariant2`
- `DocumentSourceWithUpload`
- `DocumentSourceWithUploadAndZip`
- `nil` (if no type matches)


# OpenapiClient::RecipientAddressSource

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'openapi_client'

OpenapiClient::RecipientAddressSource.openapi_one_of
# =>
# [
#   :'RecipientAddress',
#   :'RecipientAddressSourceOneOf',
#   :'RecipientAddressSourceOneOf1'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'openapi_client'

OpenapiClient::RecipientAddressSource.build(data)
# => #<RecipientAddress:0x00007fdd4aab02a0>

OpenapiClient::RecipientAddressSource.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `RecipientAddress`
- `RecipientAddressSourceOneOf`
- `RecipientAddressSourceOneOf1`
- `nil` (if no type matches)


# DocumentSourceWithUpload


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**upload_request_id** | **int** |  | 
**document_name** | **str** |  | 

## Example

```python
from c2m_api.models.document_source_with_upload import DocumentSourceWithUpload

# TODO update the JSON string below
json = "{}"
# create an instance of DocumentSourceWithUpload from a JSON string
document_source_with_upload_instance = DocumentSourceWithUpload.from_json(json)
# print the JSON string representation of the object
print(DocumentSourceWithUpload.to_json())

# convert the object into a dict
document_source_with_upload_dict = document_source_with_upload_instance.to_dict()
# create an instance of DocumentSourceWithUpload from a dict
document_source_with_upload_from_dict = DocumentSourceWithUpload.from_dict(document_source_with_upload_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



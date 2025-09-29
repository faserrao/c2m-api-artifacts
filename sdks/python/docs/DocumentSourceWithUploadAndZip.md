# DocumentSourceWithUploadAndZip


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**upload_request_id** | **int** |  | 
**zip_id** | **int** |  | 
**document_name** | **str** |  | 

## Example

```python
from c2m_api.models.document_source_with_upload_and_zip import DocumentSourceWithUploadAndZip

# TODO update the JSON string below
json = "{}"
# create an instance of DocumentSourceWithUploadAndZip from a JSON string
document_source_with_upload_and_zip_instance = DocumentSourceWithUploadAndZip.from_json(json)
# print the JSON string representation of the object
print(DocumentSourceWithUploadAndZip.to_json())

# convert the object into a dict
document_source_with_upload_and_zip_dict = document_source_with_upload_and_zip_instance.to_dict()
# create an instance of DocumentSourceWithUploadAndZip from a dict
document_source_with_upload_and_zip_from_dict = DocumentSourceWithUploadAndZip.from_dict(document_source_with_upload_and_zip_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



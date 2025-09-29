# DocumentSourceFromZip


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**zip_id** | **int** |  | 
**document_name** | **str** |  | 

## Example

```python
from c2m_api.models.document_source_from_zip import DocumentSourceFromZip

# TODO update the JSON string below
json = "{}"
# create an instance of DocumentSourceFromZip from a JSON string
document_source_from_zip_instance = DocumentSourceFromZip.from_json(json)
# print the JSON string representation of the object
print(DocumentSourceFromZip.to_json())

# convert the object into a dict
document_source_from_zip_dict = document_source_from_zip_instance.to_dict()
# create an instance of DocumentSourceFromZip from a dict
document_source_from_zip_from_dict = DocumentSourceFromZip.from_dict(document_source_from_zip_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



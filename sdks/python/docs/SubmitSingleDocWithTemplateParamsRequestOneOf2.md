# SubmitSingleDocWithTemplateParamsRequestOneOf2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_template** | **str** |  | 
**payment_details** | [**PaymentDetails**](PaymentDetails.md) |  | [optional] 
**tags** | **List[str]** |  | [optional] 
**document_source_identifier** | [**DocumentSourceIdentifier**](DocumentSourceIdentifier.md) |  | 
**recipient_address_sources** | [**List[RecipientAddressSource]**](RecipientAddressSource.md) |  | 

## Example

```python
from c2m_api.models.submit_single_doc_with_template_params_request_one_of2 import SubmitSingleDocWithTemplateParamsRequestOneOf2

# TODO update the JSON string below
json = "{}"
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf2 from a JSON string
submit_single_doc_with_template_params_request_one_of2_instance = SubmitSingleDocWithTemplateParamsRequestOneOf2.from_json(json)
# print the JSON string representation of the object
print(SubmitSingleDocWithTemplateParamsRequestOneOf2.to_json())

# convert the object into a dict
submit_single_doc_with_template_params_request_one_of2_dict = submit_single_doc_with_template_params_request_one_of2_instance.to_dict()
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf2 from a dict
submit_single_doc_with_template_params_request_one_of2_from_dict = SubmitSingleDocWithTemplateParamsRequestOneOf2.from_dict(submit_single_doc_with_template_params_request_one_of2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SubmitSingleDocWithTemplateParamsRequestOneOf


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_template** | **str** |  | 
**payment_details** | [**PaymentDetails**](PaymentDetails.md) |  | 
**tags** | **List[str]** |  | [optional] 
**recipient_address_sources** | [**List[RecipientAddressSource]**](RecipientAddressSource.md) |  | 

## Example

```python
from c2m_api.models.submit_single_doc_with_template_params_request_one_of import SubmitSingleDocWithTemplateParamsRequestOneOf

# TODO update the JSON string below
json = "{}"
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf from a JSON string
submit_single_doc_with_template_params_request_one_of_instance = SubmitSingleDocWithTemplateParamsRequestOneOf.from_json(json)
# print the JSON string representation of the object
print(SubmitSingleDocWithTemplateParamsRequestOneOf.to_json())

# convert the object into a dict
submit_single_doc_with_template_params_request_one_of_dict = submit_single_doc_with_template_params_request_one_of_instance.to_dict()
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf from a dict
submit_single_doc_with_template_params_request_one_of_from_dict = SubmitSingleDocWithTemplateParamsRequestOneOf.from_dict(submit_single_doc_with_template_params_request_one_of_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



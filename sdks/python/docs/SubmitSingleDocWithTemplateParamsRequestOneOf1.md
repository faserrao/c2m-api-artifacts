# SubmitSingleDocWithTemplateParamsRequestOneOf1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_template** | **str** |  | 
**payment_details** | [**PaymentDetails**](PaymentDetails.md) |  | 
**tags** | **List[str]** |  | [optional] 
**recipient_address_sources** | [**List[RecipientAddressSource]**](RecipientAddressSource.md) |  | 

## Example

```python
from c2m_api.models.submit_single_doc_with_template_params_request_one_of1 import SubmitSingleDocWithTemplateParamsRequestOneOf1

# TODO update the JSON string below
json = "{}"
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf1 from a JSON string
submit_single_doc_with_template_params_request_one_of1_instance = SubmitSingleDocWithTemplateParamsRequestOneOf1.from_json(json)
# print the JSON string representation of the object
print(SubmitSingleDocWithTemplateParamsRequestOneOf1.to_json())

# convert the object into a dict
submit_single_doc_with_template_params_request_one_of1_dict = submit_single_doc_with_template_params_request_one_of1_instance.to_dict()
# create an instance of SubmitSingleDocWithTemplateParamsRequestOneOf1 from a dict
submit_single_doc_with_template_params_request_one_of1_from_dict = SubmitSingleDocWithTemplateParamsRequestOneOf1.from_dict(submit_single_doc_with_template_params_request_one_of1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



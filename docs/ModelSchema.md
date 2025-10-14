# ModelSchema


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**string_property** | **str** | Property name&#39;s description (type is string) | [optional] 
**read_only_string_property** | **str** | Notice this only appears in the response. | [optional] [readonly] 
**write_only_string_property** | **str** | Notice this only appears in the request. | [optional] 
**min_length_string** | **str** | Property name&#39;s description (type is string) | [optional] 
**max_length_string** | **str** | Property name&#39;s description (type is string) | [optional] 
**min_and_max_length_string** | **str** | Property name&#39;s description (type is string) | [optional] 
**nullable_or_string_property** | **str** | Property name&#39;s description (type is string or null) | [optional] 
**string_enum_values** | **str** | Property name&#39;s description (type is string) | [optional] 
**string_date_time** | **datetime** | Property name&#39;s description (type is string, format is date-time) | [optional] 
**string_date** | **date** | Property name&#39;s description (type is string, format is date-time) | [optional] 
**string_email** | **str** | Property name&#39;s description (type is string, format is email) | [optional] 
**string_ip_address_v4** | **str** | Property name&#39;s description (type is string, format is ipv4 address) | [optional] 
**string_ip_address_v6** | **str** | Property name&#39;s description (type is string, format is ipv6 address) | [optional] 
**string_password** | **str** | Property name&#39;s description (type is string, format is password) | [optional] 
**string_hostname** | **str** | Property name&#39;s description (type is string, format is hostname) | [optional] 
**string_uri** | **str** | Property name&#39;s description (type is string, format is uri) | [optional] 
**string_uuid** | **str** | Property name&#39;s description (type is string, format is uuid) | [optional] 
**number_property** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_float** | **float** | Property name&#39;s description (type is number, format is float) | [optional] 
**number_double** | **float** | Property name&#39;s description (type is number, format is double) | [optional] 
**number_greater_than_or_equals** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_greater_than** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_less_than** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_less_than_or_equals** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_range** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_range_exclusive_maximum** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_range_exclusive_minimum_and_maximum** | **float** | Property name&#39;s description (type is number) | [optional] 
**number_multiple_of** | **float** | Property name&#39;s description (type is number) | [optional] 
**integer_type** | **int** | Property name&#39;s description (type is integer) | [optional] 
**integer32bit** | **int** | Property name&#39;s description (type is integer, format is int32) | [optional] 
**integer64bit** | **int** | Property name&#39;s description (type is integer, format is int64) | [optional] 
**boolean_property** | **bool** | Property name&#39;s description (type is boolean) | [optional] 

## Example

```python
from test-123.models.model_schema import ModelSchema

# TODO update the JSON string below
json = "{}"
# create an instance of ModelSchema from a JSON string
model_schema_instance = ModelSchema.from_json(json)
# print the JSON string representation of the object
print(ModelSchema.to_json())

# convert the object into a dict
model_schema_dict = model_schema_instance.to_dict()
# create an instance of ModelSchema from a dict
model_schema_from_dict = ModelSchema.from_dict(model_schema_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



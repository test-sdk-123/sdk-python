# Problem

The Problem Details JSON Object [[RFC7807](https://tools.ietf.org/html/rfc7807)].

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | A URI reference [[RFC3986](https://tools.ietf.org/html/rfc3986)] that identifies the problem type. It should provide human-readable documentation for the problem type. When this member is not present, its value is assumed to be \&quot;about:blank\&quot;. | [optional] 
**title** | **str** | A short, human-readable summary of the problem type. It SHOULD NOT change from occurrence to occurrence of the problem, except for purposes of localization. | [optional] 
**status** | **int** | The HTTP status code. | [optional] 
**detail** | **str** | A human-readable explanation specific to this occurrence of the problem. | [optional] 
**instance** | **str** | A URI reference that identifies the specific occurrence of the problem.  It may or may not yield further information if dereferenced. | [optional] 

## Example

```python
from test-123.models.problem import Problem

# TODO update the JSON string below
json = "{}"
# create an instance of Problem from a JSON string
problem_instance = Problem.from_json(json)
# print the JSON string representation of the object
print(Problem.to_json())

# convert the object into a dict
problem_dict = problem_instance.to_dict()
# create an instance of Problem from a dict
problem_from_dict = Problem.from_dict(problem_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



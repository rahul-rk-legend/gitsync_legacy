# Block 1
An embedded workflow that can receive inputs and return an output.



**Enabled:** True

**Version:** 1

**Type:** Block

**Priority:** 2

**Playbook Simulator:** False


##### Input Parameters
|Name|Default Value|
|----|-------------|


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Case Comment_2|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Get Scope Context Value_1|Action gets a value stored under a specified key in the Siemplify database. Available scopes to get context values for: Alert, Case, Global. Action is not working on Siemplify entities.|Siemplify|Get Scope Context Value|
|Siemplify_Change Priority_2|Automatically change case priority to the given input|Siemplify|Change Priority|
|Siemplify_Case Tag_2|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|


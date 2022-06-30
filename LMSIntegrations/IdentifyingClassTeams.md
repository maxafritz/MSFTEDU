# Identifying Class Teams


## Identify Class Teams created by Teams Classes LTI
Class Teams created through the Teams Classes LTI have a few specific properties that other Groups/Teams do not have. These properties should be present on both the Class and Group entities in Graph. Depending on your needs, choose one of the two methods to find the Class Teams from the LTI:

### Find 'Classes' created by Teams Classes LTI
In this method, we will be using the [educationClass](https://docs.microsoft.com/en-us/graph/api/educationclass-get?view=graph-rest-1.0&tabs=http) endpoint.


https://graph.microsoft.com/v1.0/groups?$select=displayname,id,mail,microsoft_EducationClassLmsExt,microsoft_EducationClassLmsExt&$filter=microsoft_EducationClassLmsExt/lmsCourseName+eq+'Engineering 204'
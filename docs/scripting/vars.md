# Vars

Vars allow you to set variables before request, and after your receive the response.

In the *Pre Request Variables* section, you can write any Strings, Numbers or any valid JavaScript literal.

In the *Post Response Variables* section, you can write any valid JavaScript expression. The res object is available, allowing you to declaratively parse the [response](javascript-reference.md#response) and set variables, instead of writing scripts to do the same.

For parsing the response, you can checkout the [response query](response-query.md) that allows you to easily query your response.

**Example:**
![bru vars](../assets/images/vars.png)

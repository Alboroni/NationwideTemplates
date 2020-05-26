# NationwideTemplates
Templates for Nationwide Landing Zone

ActionRules template creates an action rule scoped to the subscription that filters platform alerts in a fired state. 
Parameters :
name - name for action group
actionGroupId - Action Group ResourceId we are calling in action rule"
Severity-Array of Severities to filter on defaults to Sev 0 and Sev 1


SecureWebHook template -  Creates secure webhook action within action group using the common alert schema

Parameters - 
name- The name of the  secure webhook action group
serviceUri-Endpoint of Azure Function\webhookwe are calling
objectId- ObjectId for the Azure AD App regsitration we use to authenticate the function"
tenantId -TenantId Azure AD deploying into


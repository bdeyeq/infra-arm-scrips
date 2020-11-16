# infra-arm-scrips -ARM Templates created by HCL Team during workshop

Step 1: Open Powershell(Run as Administrator)

Step 2: Connect-AzAccount

Step 3: Set-AzContext -SubscriptionId "#####################"

Step 4 : New-AzResourceGroupDeployment -name "SQLServerDeployment" -ResourceGroupName #########-RG-Test -TemplateFile "C:\Users\#####\template.json" -TemplateParameterFile "C:\Users\######\parameters.json"

# springapps-infra


az devcenter dev environment create 
--dev-center-name myDemoDevCenter \  
--project-name team1-asae-dev \
--environment-name dev \
--environment-type dev  \
--catalog-item-name SpringApps-Enterprise \
--catalog-name SpringAppsEnvironments 
--parameters "{'springCloudInstanceName': 'springCloudInstanceName'}"


springCloudInstanceName
appInsightsName
logAnalyticsWorkspaceName
springCloudVirtualNetwork
springCloudAppSubnet
springCloudRuntimeSubnet
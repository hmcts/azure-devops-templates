# azure-devops-templates

Contains library of Azure DevOps yaml templates

## Build status
[![Build Status](https://hmctsreform.visualstudio.com/VirtualHearings/_apis/build/status/Tools/hmcts.azure-devops-templates?branchName=master)](https://hmctsreform.visualstudio.com/VirtualHearings/_build/latest?definitionId=75?branchName=master)


## Usage
### Building Angular & .Net Core solution 

Copy Example\azure-pipelines.yml in the root of the github repository together with applications source code

Make sure to select the appropriate solution type **angularDotNetCore** or **dotNetCore** in azure-pipelines.yml file.

### AAD Application registration

Use `jobs\aadAppRegistration.yml` to register AAD app, set Resource Access, set replay URLs and and provision Web App


## Linting Yaml

* run ```npm install``` at the root directory
* then execute the command ```$(npm bin)/yamllint azure-pipelines.yml```



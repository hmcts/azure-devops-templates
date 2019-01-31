# azure-devops-templates

Contains library of Azure DevOps yaml templates

## Usage

Copy Example\azure-pipelines.yml in the root of the github repository together with applications source code

Make sure to select the appropriate solution type **angularDotNetCore** or **dotNetCore** in azure-pipelines.yml file.

## Linting Yaml

* run ```npm install``` at the root directory
* then execute the command ```$(npm bin)/yamllint azure-pipelines.yml```
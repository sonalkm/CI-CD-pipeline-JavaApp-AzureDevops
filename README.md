Sample Java SpringBoot web app used to demo CI/CD using Azure DevOps and deploying to Azure App Service.

[![Build status](https://houssemdellai.visualstudio.com/Java-SpringBoot-WebApp/_apis/build/status/Java-SpringBoot-Maven-CI)](https://houssemdellai.visualstudio.com/Java-SpringBoot-WebApp/_build/latest?definitionId=96)

``

IMPORTANT NOTES :

``
---- create self hosted pool ;

--- create a new poool : create a linux vm 

-- create pat and authenticate > organisttion > user settings 

--configure and connect mypool

--server url : dev.azure.com/ramankhanna


--install maven and git on self hosted server

--- run ./run.sh to start listening

--imp note : select none in code coverage seeting in ci part

``in the release stage , while authorizing to your webapp go to advanced section > select the third option > publish webapp > select ur webapp 


imp note : while creating release : in the "arificat download" section , select the dropdown folder > drop > maven gradle > target > .jar file "
``

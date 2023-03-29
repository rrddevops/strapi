<h1 align="center">Hi 👋, I'm Rodrigo Davila</h1>
<h3 align="center">Projeto Strapi - Docker e K8s</h3>

- 🔭 O Strapi é um Serviço de Gerenciamento de Conteúdo (Content Management Service, ou CMS, em inglês) open-source e headless. Ele permite ao usuário criar APIs de alta qualidade em Javascript, tudo através de uma interface gráfica do usuário, simples e direta. [Strapi](https://docs.strapi.io/dev-docs/installation/cli)

#################setup##########
- install git [git](https://git-scm.com/downloads)
- install chocolatey [chocolatey](https://chocolatey.org/install)
- install vscode (https://code.visualstudio.com/download)
- docker install [docker](https://docs.docker.com/engine/reference/commandline/)
- minikube install [minikube](https://minikube.sigs.k8s.io/docs/start/)

**yarn and nodejs**
choco install nodejs-lts
choco install yarn

##########run app######################
yarn create strapi-app strapi --quickstart
yarn add @strapi/plugin-documentation
yarn develop

##########consumo da api########################

--Windows: </br>
Invoke-RestMethod -Uri http://localhost:1337/api/cadastros -Method GET -Headers @{
    Authorization = 'Bearer 4c1936c985f5014dbbbe3d1511b9c005cd2cdde9471d06527dc01d210f6cd6e43b7e71a52df3d6c3c7a484a52f4b434f32695f80229d369dbdfdd7bc866a84e0c67aff6883b0a1fa02239bec02a0136446dcfda00aae6a205ef268ed7ea8f06ac7818a39eb1509e6a40cd79d01d897be018da80a7fe5779a35597698a70df1fb'
    'Content-Type' = 'application/json'
    Accept = 'application/json'
} | ConvertTo-Json

--linux: </br>
curl -X 'GET' \
  'http://192.168.5.82:1337/api/cadastros' \
  -H 'accept: application/json' \
  -H 'Authorization: Bearer 4c1936c985f5014dbbbe3d1511b9c005cd2cdde9471d06527dc01d210f6cd6e43b7e71a52df3d6c3c7a484a52f4b434f32695f80229d369dbdfdd7bc866a84e0c67aff6883b0a1fa02239bec02a0136446dcfda00aae6a205ef268ed7ea8f06ac7818a39eb1509e6a40cd79d01d897be018da80a7fe5779a35597698a70df1fb'

#######################################

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/rodrigordavila" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="rodrigordavila" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://circleci.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=rrddevops&show_icons=true&locale=en&layout=compact" alt="rrddevops" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=rrddevops&show_icons=true&locale=en" alt="rrddevops" /></p>

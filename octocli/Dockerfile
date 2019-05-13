FROM octopusdeploy/octo

LABEL "com.github.actions.name"="Octopus CLI"
LABEL "com.github.actions.description"="Execute the Octopus CLI as a GitHub Action"
LABEL "com.github.actions.icon"="package"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="https://github.com/mcasperson/OctopusDeployGithubAction"
LABEL "homepage"="https://github.com/mcasperson/OctopusDeployGithubAction"
LABEL "maintainer"="Matthew Casperson <matthewcasperson@gmail.com>"

WORKDIR /src
ENTRYPOINT ["dotnet", "/octo/Octo.dll"]
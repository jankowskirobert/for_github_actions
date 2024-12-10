# for_github_actions

What is a purpouse/ main drivers for:
- being able to build and deploy via github actions
- automate
- unified repo containing everything CI/CD def, IaC, code, instructions

Steps:
- remote runner is gonna build infra
- [github aciton -> spawn runner -> init tofu -> build target infra -> deploy app]

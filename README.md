# GitHub Projects

**Author:** Carlos Biagolini-Jr.

**LinkedIn:** [https://www.linkedin.com/in/biagolini/](https://www.linkedin.com/in/biagolini/)

**Medium:** [https://medium.com/@biagolini](https://medium.com/@biagolini)

[EN]: This repository serves as an index for various GitHub-focused projects and code examples, centered on GitHub Actions pipelines and their integration with AWS. Each linked repository demonstrates a different aspect of building and securing CI/CD workflows, including reusable workflows, OpenID Connect authentication to AWS, and defenses against secret exfiltration. The goal is to provide practical examples that can be used as references for learning and development. For more in-depth discussions and technical articles, visit my LinkedIn and Medium profiles.

[PT]: Este repositório serve como um índice para diversos projetos e exemplos de código voltados ao GitHub, com foco em pipelines do GitHub Actions e sua integração com a AWS. Cada repositório vinculado demonstra um aspecto diferente da construção e proteção de fluxos de CI/CD, incluindo workflows reutilizáveis, autenticação via OpenID Connect com a AWS e defesas contra a exfiltração de segredos. O objetivo é fornecer exemplos práticos que possam servir como referência para aprendizado e desenvolvimento. Para discussões mais aprofundadas e artigos técnicos, visite meus perfis no LinkedIn e no Medium.

---

## A

### Actions

#### Platform Workflows

The central reusable workflow for the secret exfiltration defense article. It splits a pipeline into a credential-free build job and a publish job that never runs the caller's code and holds the AWS credentials, obtained through GitHub OIDC with a short-lived session.

[https://github.com/biagolini/GithubActionsPlatformWorkflows](https://github.com/biagolini/GithubActionsPlatformWorkflows)

#### Secret Attacker Workflows

The attacker-controlled repository for the secret exfiltration defense article. It holds a reusable workflow that prints whatever secret a caller forwards to it, demonstrating how a pipeline can run code from another repository and leak a secret that never appears in the service repository.

[https://github.com/biagolini/GithubActionsSecretAttackerWorkflows](https://github.com/biagolini/GithubActionsSecretAttackerWorkflows)

#### Secret Defense

The service repository for the secret exfiltration defense article. A minimal Python project packaged as a container, with before-and-after workflows that show how a writer can leak secrets or steal an AWS role session, and how a tiered pipeline design stops it.

[https://github.com/biagolini/GithubActionsSecretDefense](https://github.com/biagolini/GithubActionsSecretDefense)

## B

## C

## D

## E

## F

## G

## H

## I

## J

## K

## L

## M

## N

## O

## P

## Q

## R

## S

## T

## U

## V

## W

## X

## Y

## Z

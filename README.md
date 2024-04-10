# Automate Terraform with GitHub Actions

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).

## Imagens do Terraform em funcionamemto 

As imagens a seguir são correspondentes ao tutorial de terraform, que funcionou de forma adequada. 

Temos imagens do terraform com o que foi esperado e depois elas funcionando após o merge no github com o github actions

<img src="./Assets/picture6.jpeg"></img>

<img src="./Assets/picture4.jpeg"></img>

<img src="./Assets/picture1.jpeg"></img>

<img src="./Assets/picture2.jpeg"></img>

<img src="./Assets/picture3.jpeg"></img>

<img src="./Assets/picture5.jpeg"></img>

O tutorial explica como configurar um fluxo de trabalho automatizado para gerenciar a infraestrutura como código. A ideia principal é integrar o Terraform, com o GitHub Actions, uma plataforma de automação e CI/CD (Integração Contínua e Entrega Contínua) que permite automatizar fluxos de trabalho diretamente no repositório do GitHub.

O processo começa com a criação de um repositório no GitHub que contém os arquivos de configuração do Terraform. Esses arquivos definem a infraestrutura desejada, como servidores, redes e serviços em nuvem. Em seguida, é configurado um arquivo de fluxo de trabalho do GitHub Actions que especifica as etapas a serem executadas automaticamente sempre que ocorrerem certos eventos no repositório, como um push ou um pull request.

O fluxo de trabalho do GitHub Actions geralmente inclui etapas como:

Inicialização do Terraform: Prepara o ambiente do Terraform, carregando os módulos e configurando os provedores de serviços em nuvem.

Validação: Verifica se os arquivos de configuração do Terraform estão sintaticamente corretos e não contêm erros.

Plano: Gera um plano de execução, mostrando quais ações serão realizadas na infraestrutura quando o Terraform for aplicado. Isso é útil para revisão em pull requests.

Aplicação: Aplica as alterações na infraestrutura conforme definido nos arquivos de configuração do Terraform. Esta etapa é geralmente executada manualmente ou em um ambiente seguro para evitar alterações acidentais na infraestrutura.
Ao integrar o Terraform com o GitHub Actions, você pode automatizar o processo de gerenciamento de infraestrutura, tornando-o mais rápido, consistente e seguro. Isso permite que as equipes de desenvolvimento e operações colaborem de forma mais eficaz e mantenham a infraestrutura atualizada com as mudanças no código de forma automatizada.


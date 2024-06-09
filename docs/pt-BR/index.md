# Introdução

![high-level](./pictures/diagrams-high-level-simple.png)

**External Secrets Operator** (conhecido como ESO) é um operator para Kubernetes que se integra com sistemas de gerenciamento de <em>secrets</em> como [AWS Secrets
Manager](https://aws.amazon.com/secrets-manager/), [HashiCorp
Vault](https://www.vaultproject.io/), [Google Secrets
Manager](https://cloud.google.com/secret-manager), [Azure Key
Vault](https://azure.microsoft.com/en-us/services/key-vault/), [IBM Cloud Secrets Manager](https://www.ibm.com/cloud/secrets-manager), [CyberArk Conjur](https://www.conjur.org) e muitos outros. O <em>operator</em> lê as informações de APIs externas e automaticamente as injeta como `values` na forma de um [Kubernetes
Secret](https://kubernetes.io/docs/concepts/configuration/secret/).

### Qual é o objetivo do External Secrets Operator?

O objetivo do External Secrets Operator é sincronizar segredos de uma API externa para o Kubernetes. ESO é uma coleção de recursos de API customizadas: `ExternalSecret`, `SecretStore` and `ClusterSecretStore`, que provê uma abstração amigável às APIs externas que guardam e gerenciam o ciclo de vida dos segredos para você.

### Como começar?

Para começar, primeiro leia a [API overview](introduction/overview), isso deve ser o suficiente para que possa entender as linhas gerais da API e seus  principais casos de uso. Em seguida, siga um dos [guias](guides/introduction) para começar a usar o operator. Veja também [o guia de instalação](introduction/getting-started) para instruções de setup.

Para ter acesso a todas as <em>API types</em>, veja [especificação de API](api/spec.md).


### Como se envolver no projeto?

This project is driven by its users and contributors, and we welcome everybody
to get involved. Join our meetings, open issues or ask questions in Slack. The
success of this project depends on your input: No contribution is too small -
even opinions matter!

How to get involved:

- Bi-weekly Development Meeting every odd week at [8:00 PM Berlin Time](https://dateful.com/time-zone-converter?t=20:00&tz=Europe/Berlin) on Wednesday
  ([agenda](https://hackmd.io/GSGEpTVdRZCP6LDxV3FHJA), [jitsi call](https://meet.jit.si/eso-community-meeting))
- [Kubernetes Slack
  #external-secrets](https://kubernetes.slack.com/messages/external-secrets)
- [Contributing Process](contributing/process)
- [Twitter](https://twitter.com/ExtSecretsOptr)

### Começado por

![godaddy-logo](./pictures/godaddy_logo.png)

### Patrocinado por

![cs-logo](./pictures/cs_logo.png)
![Form3](./pictures/form3_logo.png)
![Pento](./pictures/pento_logo.png)

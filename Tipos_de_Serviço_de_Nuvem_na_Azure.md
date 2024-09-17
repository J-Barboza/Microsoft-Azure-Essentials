
## Tipos de Serviço de Nuvem

#### IaaS - Infraestrutura como Serviço
Com IaaS, você pode "alugar" a infraestrutura de TI que precisa, como servidores, máquinas virtuais, armazenamento e redes, tudo de um provedor de nuvem. A vantagem? Você só paga pelo que usar, como se estivesse alugando o espaço e os recursos conforme a necessidade, sem precisar se preocupar em manter essa estrutura fisicamente.

![Tipo Iaas](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/tipo_de_servico_IaaS.png)


#### PaaS - Plataforma como Serviço
O PaaS oferece um ambiente completo para você criar, testar e lançar seus aplicativos sem precisar se preocupar com a infraestrutura (servidores, rede, etc.). É como se você tivesse um espaço pronto para desenvolver seu software, sem perder tempo gerenciando a parte "chata" do sistema.
![Tipo Paas](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/tipo_de_servico_PaaS.png)

#### SaaS - Software como Serviço
SaaS é quando você usa aplicativos direto na nuvem, acessados pela internet, sem precisar instalar nada no seu computador. Exemplos conhecidos são o Microsoft Office 365, serviços de email e calendários. Você só precisa de uma conexão com a internet, e pronto, tudo funcionando.
![Tipo Saas](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/tipo_de_servico_SaaS.png)

### Modelo de Responsabilidade Compartilhada

No mundo da computação em nuvem, tanto o provedor de serviços quanto você, como cliente, têm responsabilidades diferentes para garantir a segurança e o bom funcionamento dos recursos que você usa. Isso é o que chamamos de **Modelo de Responsabilidade Compartilhada**.

Imagine que o provedor de nuvem (como o Azure) cuida de toda a infraestrutura que você está usando, como servidores físicos, rede e segurança básica. Esse é o papel dele no modelo. Mas, como você está rodando seus aplicativos e armazenando seus dados na nuvem, também tem algumas responsabilidades.

#### Como funciona?

1. **Azure**:
   - Garante que a infraestrutura seja segura, atualizada e funcionando 24/7.
   - Mantém os servidores, armazenamento, redes e data centers.
   - Cuida de atualizações de segurança básicas e da integridade física dos recursos.

2. **Cliente**:
   - Gerencia o que roda na nuvem, como aplicativos, dados, sistemas operacionais e configurações de segurança.
   - Define quem pode acessar seus dados e como eles são protegidos.
   - Cuida de senhas, permissões, e garante que suas aplicações estejam seguras.

Dependendo do modelo de serviço que você está usando (IaaS, PaaS ou SaaS), suas responsabilidades podem variar. Por exemplo:
- No **IaaS**, você é responsável por quase tudo no nível de software, enquanto o provedor cuida da infraestrutura física.
- No **PaaS**, o provedor gerencia mais coisas (como o sistema operacional), e você foca no desenvolvimento do seu aplicativo.
- No **SaaS**, a maior parte das responsabilidades fica com o provedor, e você só se preocupa em usar o aplicativo de forma segura.

![Modelo de serviço compartilhado](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Modelo_de_responsabilidade_compartilhada.png)
---




#### Links para Estudar

##### [Introdução aos Tipos de Serviço](https://learn.microsoft.com/training/modules/describe-cloud-service-types/1-introduction )
##### [Infraestrutura IaaS](https://learn.microsoft.com/training/modules/describe-cloud-service-types/2-describe-infrastructure-service)
##### [Infraestrutura PaaS](https://learn.microsoft.com/training/modules/describe-cloud-service-types/3-describe-platform-service)
##### [Infraestrutura PaaS](https://learn.microsoft.com/training/modules/describe-cloud-service-types/4-describe-software-service)

---
[Voltar à Página Principal](README.md)
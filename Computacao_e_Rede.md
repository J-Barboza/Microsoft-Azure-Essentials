# Módulo 2: Arquitetura e Serviços

## Computação e Rede

### Serviços de Computação do Azure

#### Computação do Azure
A Computação do Azure é um serviço sob demanda que fornece recursos como discos, processadores, memória, rede e sistemas operacionais. É como "alugar" a infraestrutura de TI que você precisa, sem precisar comprar ou manter servidores físicos.

![Serviços de Computação](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/develop/images/Servicos_de_Computacao.png)

### Máquinas Virtuais (VMs)
As **Máquinas Virtuais (VMs)** no Azure são como versões digitais de computadores físicos. Elas incluem processador, memória, armazenamento e rede. Como uma oferta de **IaaS**, elas permitem total controle e personalização.

### Conjuntos de Dimensionamento de VMs
Os **Conjuntos de Dimensionamento de VMs** permitem que você faça o balanceamento de carga e ajuste automaticamente a quantidade de recursos que sua aplicação usa. 
- Escale para cima quando precisar de mais recursos.
- Escale para baixo quando puder economizar recursos.

### Conjuntos de Disponibilidade de VMs
Esses conjuntos garantem que suas máquinas virtuais estejam disponíveis mesmo se um dos datacenters falhar, separando-as fisicamente dentro da mesma região.

![Conjunto de Disponibilidade](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/develop/images/Conjunto_de_disponibilidade_de_VM.png)

### Área de Trabalho Virtual do Azure
A **Área de Trabalho Virtual do Azure** oferece um ambiente de desktop e aplicativos virtualizados rodando na nuvem.
- Crie um ambiente completo de virtualização sem precisar configurar servidores extras.
- Ofereça suporte a múltiplas sessões para vários usuários ao mesmo tempo.

### Serviços de Contêineres
Os **contêineres do Azure** oferecem um ambiente virtualizado leve que roda sem a necessidade de gerenciar o sistema operacional completo.
- **Instâncias de Contêiner do Azure**: PaaS que roda contêineres individuais ou múltiplos (pods).
- **Aplicativos de Contêiner do Azure**: PaaS que inclui balanceamento de carga e escalabilidade.
- **Serviço de Kubernetes do Azure**: Ideal para gerenciar grandes quantidades de contêineres com arquitetura distribuída.

### Azure Functions
As **Azure Functions** são uma solução de computação sem servidor. O código é executado em resposta a eventos, e você só paga pelo tempo de execução, sem se preocupar com a infraestrutura.

### Comparar Opções de Computação

#### Máquinas Virtuais
- Servidor baseado na nuvem que suporta ambientes **Windows** ou **Linux**.
- Útil para migrações de sistemas completos para a nuvem, o famoso **lift-and-shift**.

#### Área de Trabalho Virtual
- Fornece uma experiência completa de **desktop Windows** na nuvem.
- Pode ser acessada por aplicativos dedicados ou via navegadores modernos.

#### Contêineres
- Ambiente leve e perfeito para **microsserviços**.
- Projetado para **escalabilidade** e **resiliência**.
- Vários contêineres podem rodar em um único sistema operacional host.

#### Serviços de Aplicativo
Os **Serviços de Aplicativo do Azure** são uma plataforma totalmente gerenciada para criar, implantar e escalar rapidamente **aplicações web** e **APIs**. Funciona com tecnologias como **.NET**, **Node.js**, **Java**, **Python** e **PHP**.

### Serviços de Rede

#### Rede Virtual do Azure (VNet)
A **VNet** permite que seus recursos no Azure se comuniquem entre si, com a Internet e com redes locais.
- **Pontos de extremidade públicos**: acessíveis de qualquer lugar na Internet.
- **Pontos de extremidade privados**: acessíveis apenas dentro da sua rede privada.
- Sub-redes virtuais para segmentar sua rede de acordo com as suas necessidades.
- Emparelhamento de redes conecta suas redes privadas diretamente.

#### Gateway de VPN
O **Gateway de VPN** permite que você envie tráfego criptografado entre sua **rede virtual no Azure** e sua rede local pela Internet.

![Gateway de VPN](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/develop/images/Gateway_de_VPN.png)

#### ExpressRoute
O **ExpressRoute** conecta sua rede local ao Azure por meio de uma conexão privada, sem passar pela Internet pública, oferecendo mais segurança e desempenho.

![ExpressRoute](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/develop/images/ExpressRoute.png)

#### DNS do Azure
O **DNS do Azure** oferece confiabilidade e desempenho utilizando uma rede global de servidores DNS com **Anycast**.
- Facilita o gerenciamento de domínios externos e do Azure com um único serviço.
- Permite a personalização de nomes de domínio privados em redes virtuais privadas.
- Suporte a **registros de alias** para apontar diretamente para recursos do Azure.

---
[Voltar à Página Principal](README.md)
# Módulo 2: Arquitetura e Serviços

## Componentes de Arquitetura 

### Regiões
O Azure tem mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países. As regiões são formadas por um ou mais datacenters muito próximos uns dos outros, proporcionando flexibilidade e escala para reduzir a latência (tempo de resposta) para os clientes. Além disso, garantem que os dados permaneçam dentro das regulamentações locais, oferecendo uma conformidade robusta.
![Regioes](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Mapa_de_regioes.png)

### Zonas de Disponibilidade
As **zonas de disponibilidade** protegem seus serviços contra possíveis falhas de um datacenter. Cada zona é composta por datacenters fisicamente separados dentro da mesma região. Esses datacenters têm alimentação, resfriamento e redes independentes, conectados por redes privadas de fibra óptica, garantindo alta disponibilidade e resiliência.
![Zona de Disponibilidade](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Zonas_de_disponibilidade.png)

### Pares de Regiões
As **regiões emparelhadas** estão separadas por, no mínimo, 300 milhas (cerca de 480 km) e oferecem replicação automática para alguns serviços. Em caso de interrupção, uma região do par tem prioridade para recuperação. Além disso, as atualizações são feitas de maneira gradual entre as regiões emparelhadas, minimizando o tempo de inatividade.

[Link para mais informações sobre pares de regiões](https://aka.ms/PairedRegions-ptb)

![Pares de Regioes](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Pares_de_regioes.png)

### Regiões Soberanas do Azure

#### Serviços Governamentais dos EUA
Esses serviços são desenhados para atender às exigências de segurança e conformidade das agências federais, governos estaduais e locais dos EUA, bem como seus provedores de soluções.

#### Azure Governamental
É uma instância separada do Azure, fisicamente isolada de outras implantações. Só pode ser acessada por pessoal autorizado e verificado, garantindo um ambiente seguro e adequado para as operações governamentais.

### Recursos do Azure
Os **recursos do Azure** são os componentes que você pode usar para construir suas soluções na nuvem, como armazenamento, máquinas virtuais e redes.
![Recursos de Azure](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Recursos_do_Azure.png)


### Grupos de Recursos
Um **grupo de recursos** é um contêiner usado para gerenciar e organizar recursos em uma única unidade. Alguns pontos importantes:
- Os recursos podem existir em apenas um grupo de recursos.
- Eles podem estar em diferentes regiões.
- Os recursos podem ser movidos entre diferentes grupos de recursos.
- Aplicações podem utilizar múltiplos grupos de recursos.
![Grupo de Recursos](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Grupo_de_Recursos.png)

### Assinaturas do Azure
Uma **assinatura do Azure** dá a você acesso autenticado e autorizado às contas do Azure. Ela também possui algumas funções importantes:
- **Limite de cobrança**: você pode gerar relatórios de cobrança e faturas separadas para cada assinatura.
- **Limite de controle de acesso**: permite gerenciar e controlar o que os usuários podem provisionar com suas assinaturas específicas.
![Assinaturas de Azure](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Assinatura_do_Azure.png)

### Grupos de Gerenciamento
Os grupos de gerenciamento podem incluir várias assinaturas do Azure. Qualquer política ou configuração aplicada ao grupo de gerenciamento será herdada por todas as assinaturas dentro dele, facilitando a administração centralizada de várias contas.

![Grupos de Gerenciamento](https://github.com/J-Barboza/Microsoft-Azure-Essentials/blob/main/images/Grupos_de_gerenciamento.png)
---
[Voltar à Página Principal](README.md)
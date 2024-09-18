## Módulo: Criando Recursos e Dimensionamento de Máquinas Virtuais no Azure

Neste módulo, vamos detalhar a criação de alguns dos principais recursos do Azure: Máquinas Virtuais, Área de Trabalho Virtual e Aplicativos de Funções, além de entender como dimensionar esses recursos conforme a demanda.

### 1. Criando uma Máquina Virtual (VM) no Azure

Uma **Máquina Virtual (VM)** é um computador completo que você pode rodar na nuvem. Com ela, você pode instalar sistemas operacionais, aplicativos, e até rodar serviços web. Aqui, você vai aprender como criar uma do zero.

#### Passos para criar uma Máquina Virtual:
1. **Acesse o Portal do Azure**: Entre no [portal do Azure](https://portal.azure.com) com sua conta.
2. **Crie um novo recurso**: No canto superior esquerdo, clique em **Criar um Recurso**.
3. **Selecione 'Máquina Virtual'**: Pesquise por "Máquina Virtual" e clique na opção que aparecer.
4. **Configurações básicas**:
   - **Nome**: Dê um nome à sua VM (ex: `minhaVM`).
   - **Região**: Escolha a região onde sua VM será hospedada. É recomendável escolher a mais próxima de você para reduzir a latência.
   - **Imagem**: Selecione o sistema operacional da sua VM (ex: Windows ou Linux).
   - **Tamanho**: Escolha o tamanho (número de processadores, memória etc.) de acordo com a necessidade. O Azure vai sugerir tamanhos baseados na sua escolha de sistema operacional.
   - **Usuário e Senha**: Defina o nome de usuário e a senha que você vai usar para acessar sua VM.
5. **Configurações adicionais**:
   - **Rede**: Defina as configurações de rede, como a criação de um IP público para acessar a VM.
   - **Armazenamento**: Escolha o tipo de disco (padrão ou SSD) e o tamanho do armazenamento que a VM vai usar.
6. **Revise e Crie**: Depois de revisar todas as configurações, clique em **Criar**.

Após alguns minutos, sua Máquina Virtual estará pronta e você poderá acessá-la através de um cliente de desktop remoto (no caso do Windows) ou via SSH (no caso do Linux).

---

### 2. Criando uma Área de Trabalho Virtual (Azure Virtual Desktop)

A **Área de Trabalho Virtual do Azure** permite que você acesse um desktop completo diretamente da nuvem. É uma ótima solução para trabalho remoto ou para acessar aplicações de forma centralizada, sem depender de um dispositivo específico.

#### Passos para criar uma Área de Trabalho Virtual:
1. **Acesse o Portal do Azure**: Vá para o [portal do Azure](https://portal.azure.com).
2. **Criar um Recurso**: No menu, clique em **Criar um Recurso** e procure por **Área de Trabalho Virtual**.
3. **Criação do Pool de Hosts**:
   - **Nome do Pool**: Dê um nome ao conjunto de máquinas que rodarão as áreas de trabalho.
   - **Região**: Escolha a região onde seus hosts serão criados.
   - **Imagem**: Escolha a imagem de sistema operacional para os desktops (geralmente o Windows 10/11).
4. **Configurações de rede e segurança**:
   - **Rede Virtual**: Escolha uma rede virtual que permitirá o acesso à sua Área de Trabalho Virtual.
   - **Segurança**: Configure as permissões de acesso, definindo quem pode acessar os desktops virtuais.
5. **Configurações adicionais**: Escolha se quer permitir múltiplas sessões por máquina (vários usuários em uma VM) e configure o armazenamento para perfis de usuário.
6. **Criação e Acesso**: Após criar, você pode acessar a área de trabalho virtual diretamente por um aplicativo de conexão de área de trabalho remota ou via navegador.

Agora você tem uma área de trabalho pronta para ser acessada de qualquer dispositivo com conexão à internet, seja para uso pessoal ou para uma equipe.

---

### 3. Criando Aplicativos de Funções (Azure Functions)

As **Azure Functions** são perfeitas para tarefas automáticas ou baseadas em eventos, sem que você precise gerenciar servidores. Com elas, você pode executar código quando necessário, economizando recursos.

#### Passos para criar uma Azure Function:
1. **Acesse o Portal do Azure**: Acesse o [portal do Azure](https://portal.azure.com).
2. **Criar um Recurso**: No menu, clique em **Criar um Recurso** e pesquise por **Funções**.
3. **Escolha o Modelo de Função**:
   - Você pode escolher funções baseadas em eventos HTTP, timers ou até integrações com outros serviços, como armazenamento de blobs ou filas.
4. **Configurações Básicas**:
   - **Nome**: Dê um nome à sua aplicação de função.
   - **Região**: Escolha a região onde a função será executada.
   - **Plano de Hospedagem**: Escolha o plano de execução (consumo, premium ou dedicado). O mais comum é o de **consumo**, que cobra apenas pelo tempo de execução.
   - **Código ou Repositório**: Você pode escolher escrever o código diretamente no portal do Azure ou integrar um repositório como o GitHub para versionar e gerenciar suas funções.
5. **Escrevendo a Função**:
   - No editor de código, escreva a lógica da sua função. Por exemplo, uma função HTTP poderia responder a uma solicitação web.
6. **Teste e Execute**: Após criada, você pode testar a função diretamente no portal ou chamar seu endpoint para ver os resultados.

Com as **Azure Functions**, você pode construir automações poderosas que escalam com base na demanda.

---

### Dimensionamento de Máquinas Virtuais no Azure

Dimensionar uma máquina virtual significa ajustar os recursos que ela usa, como poder de processamento, memória e armazenamento. O Azure facilita esse ajuste de duas formas:

1. **Escalar para cima**: Aumenta os recursos quando sua aplicação ou serviço precisa de mais poder, como em momentos de alto tráfego.
2. **Escalar para baixo**: Reduz os recursos quando a demanda diminui, ajudando a economizar custos.

#### Como fazer isso:
- **Manual**: Você pode ajustar os recursos manualmente no portal do Azure, indo até a máquina virtual e alterando o tamanho ou o tipo da VM.
- **Automático**: Configure escalonamento automático para que o Azure ajuste os recursos com base em métricas, como uso de CPU ou memória, garantindo que você nunca use mais do que precisa.

Esse processo é essencial para garantir que seus aplicativos rodem de forma eficiente e econômica.

---
[Voltar à Página Principal](README.md)
# Armazenamento no Azure

## Contas de Armazenamento
- Deve ter um nome exclusivo globalmente.
- Fornece acesso à Internet em todo o mundo.
- Determina os serviços de armazenamento e as opções de redundância.

---

## Redundância de Armazenamento
![Redundância de Armazenamento](images\Redundancia_de_Armazenamento.png)  
![Redundância de Armazenamento por Região](images\Redundancia_de_Armazenamento_Regiao.png)

---

## Serviços de Armazenamento

- **Blob do Azure**: Otimizado para o armazenamento de grandes quantidades de dados não estruturados, como texto ou dados binários.
- **Disco do Azure**: Fornece discos para máquinas virtuais, aplicativos e outros serviços utilizarem.
- **Fila do Azure**: Armazena e recupera grandes volumes de mensagens, cada uma com até 64 KB.
- **Arquivos do Azure**: Configura um compartilhamento de arquivos de rede que pode ser mapeado e acessado como um drive em estações de trabalho.
- **Tabelas do Azure**: Fornece uma opção para armazenar dados não relacionais com um design sem esquema, ideal para dados de chave/atributo.

---

## Pontos de Extremidade Públicos do Serviço de Armazenamento
![Pontos de Extremidade Públicos](images\Pontos_de_Extremidade_de_Armazenamento.png)

---

## Camadas de Acesso de Armazenamento
![Camadas de Acesso de Armazenamento](images\Camadas_de_Acesso_de_Armazenamento.png)

---

## Migrações
- **Plataforma de Migração Unificada**: Usa uma variedade de ferramentas integradas e autônomas.
- **Avaliação e Migração**: Facilita a transição para o Azure, com ferramentas para avaliar e migrar dados.

---

## Azure Data Box
- Armazena até **80 terabytes** de dados.
- Ideal para mover backups de recuperação de desastres para o Azure.
- Protege dados durante o transporte com uma caixa robusta.
- Usado para migração de dados para conformidade ou necessidades regulatórias.
- Perfeito para locais remotos com conectividade limitada.

![Azure Data Box](images\Azure_Data_Box.png)  
![Mapa do Azure Data Box](images\Azure_Data_Box_Mapa.png)

---

## Opções de Gerenciamento de Arquivos

### **AzCopy**
- Ferramenta de linha de comando.
- Copia blobs ou arquivos de/para a conta de armazenamento.
- Suporta sincronização em uma direção.

### **Gerenciador de Armazenamento do Azure**
- Interface gráfica amigável, semelhante ao Windows Explorer.
- Compatível com **Windows**, **macOS** e **Linux**.

### **Sincronização de Arquivos do Azure**
- Sincroniza arquivos entre o Azure e ambientes locais de forma bidirecional.
- A camada de nuvem armazena arquivos acessados com frequência no local, liberando espaço.
---
[Voltar à Página Principal](README.md)
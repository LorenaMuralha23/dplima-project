# Requisitos

## 1. Objetivo

A primeira versão da plataforma deve oferecer uma presença digital pública para o negócio de serviços de despachante de veículos, permitindo que potenciais clientes encontrem informações sobre os serviços oferecidos e iniciem contato pelos canais de atendimento disponíveis.

O foco inicial é apresentar informações de forma clara, facilitar a descoberta do negócio pela internet e reduzir a necessidade de contato apenas para esclarecimento de dúvidas básicas.

---

## 2. Requisitos Funcionais

### RF-01 — Acesso público

A plataforma deve permitir acesso público às informações do negócio, sem exigir autenticação.

**Status:** Confirmed

---

### RF-02 — Apresentação dos serviços

A plataforma deve apresentar os serviços oferecidos pelo negócio de maneira clara e organizada.

Cada serviço deve possuir informações suficientes para que o cliente consiga identificar se ele atende à sua necessidade.

**Status:** Confirmed

**To be defined:**
- lista oficial de serviços;
- categorização dos serviços;
- ordem e forma de apresentação.

---

### RF-03 — Detalhamento dos serviços

A plataforma deve permitir a exibição de informações relevantes sobre cada serviço oferecido.

Essas informações podem incluir:

- descrição do serviço;
- documentos ou requisitos necessários;
- prazo estimado, quando aplicável;
- valor ou faixa de preço, quando aplicável;
- orientações importantes antes do atendimento.

**Status:** Confirmed

**To be defined:**
- quais informações serão obrigatórias para todos os serviços;
- quais serviços possuirão valores fixos ou faixas de preço;
- quais documentos serão necessários para cada serviço.

---

### RF-04 — Exibição dos canais de contato

A plataforma deve disponibilizar os canais de contato utilizados pelo negócio.

Os canais podem incluir:

- WhatsApp;
- telefone;
- e-mail;
- Instagram.

**Status:** Confirmed

**To be defined:**
- quais canais serão disponibilizados na primeira versão.

---

### RF-05 — Início de contato via WhatsApp

A plataforma deve permitir que o cliente inicie facilmente uma conversa com o negócio por meio do WhatsApp.

**Status:** Confirmed

**To be defined:**
- utilização ou não de mensagens pré-preenchidas;
- contexto enviado junto ao início da conversa.

---

### RF-06 — Informações de localização

A plataforma deve disponibilizar informações que permitam ao cliente identificar a localização física do negócio.

Essas informações podem incluir:

- endereço;
- referências de localização;
- integração ou direcionamento para serviços de mapas.

**Status:** Confirmed

---

### RF-07 — Informações institucionais

A plataforma deve apresentar informações básicas sobre o negócio que contribuam para a confiança do cliente.

Essas informações podem incluir:

- nome do estabelecimento;
- descrição do negócio;
- horário de atendimento;
- formas de atendimento;
- tempo de atuação, quando aplicável.

**Status:** Confirmed

---

## 3. Requisitos Não Funcionais

### RNF-01 — Responsividade

A plataforma deve funcionar adequadamente em diferentes tamanhos de tela, com prioridade para dispositivos móveis.

**Status:** Confirmed

---

### RNF-02 — Usabilidade

A interface deve permitir que o usuário encontre rapidamente informações sobre serviços, valores, localização e canais de contato.

A navegação deve ser simples e objetiva.

**Status:** Confirmed

---

### RNF-03 — Acessibilidade

A plataforma deve considerar práticas básicas de acessibilidade, incluindo:

- boa legibilidade;
- contraste adequado;
- estrutura semântica;
- navegação compreensível;
- textos alternativos para imagens relevantes.

**Status:** Confirmed

---

### RNF-04 — Desempenho

A plataforma deve apresentar carregamento rápido e navegação fluida, principalmente em dispositivos móveis e conexões de internet comuns.

Métricas específicas de desempenho poderão ser definidas posteriormente.

**Status:** Confirmed

---

### RNF-05 — Segurança

A aplicação deve adotar práticas básicas de segurança adequadas a uma plataforma pública.

Informações sensíveis, credenciais, tokens e chaves de acesso não devem ser expostos no código-fonte público da aplicação.

**Status:** Confirmed

---

### RNF-06 — Manutenibilidade

A solução deve possuir uma estrutura que facilite:

- atualização de conteúdo;
- inclusão de novos serviços;
- alteração de informações existentes;
- evolução futura da aplicação.

**Status:** Confirmed

---

### RNF-07 — SEO e descoberta

A plataforma deve ser estruturada de forma a facilitar sua indexação por mecanismos de busca.

Deve haver atenção especial à descoberta local do negócio por usuários que procuram serviços de despachante na região de Petrópolis, RJ.

**Status:** Confirmed

**To be defined:**
- palavras-chave;
- estratégia de SEO local;
- estrutura de páginas;
- metadados;
- integração com presença digital externa.

---

## 4. Fora do Escopo da Primeira Versão

Os seguintes recursos não fazem parte do escopo inicial:

- autenticação de clientes;
- área do cliente;
- contas de funcionários;
- painel administrativo;
- armazenamento de documentos de clientes;
- upload de documentos;
- processamento interno de solicitações;
- acompanhamento de processos;
- pagamentos online;
- agendamento online;
- automação do fluxo operacional do despachante;
- integração com sistemas internos complexos.

Esses recursos poderão ser avaliados futuramente conforme as necessidades do negócio.

---

## 5. Itens em Aberto

Os seguintes pontos ainda precisam ser definidos:

- lista oficial de serviços;
- informações obrigatórias de cada serviço;
- preços fixos, faixas de preço ou serviços sem divulgação de valor;
- documentos necessários para cada serviço;
- prazos estimados;
- horário oficial de atendimento;
- canais de contato disponibilizados;
- informações institucionais;
- identidade visual;
- necessidade futura de formulário de contato;
- necessidade futura de agendamento;
- necessidade futura de painel administrativo;
- necessidade de persistência de dados;
- exigências legais ou regulatórias aplicáveis ao conteúdo disponibilizado.

Todos os itens acima permanecem como **To be defined** até que sejam validados com o responsável pelo negócio.
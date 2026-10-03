# Decisões de Arquitetura

## Contexto

O repositório contém atualmente apenas uma breve descrição de negócio e nenhum artefato de implementação. Por isso, a arquitetura é documentada como um conjunto inicial de decisões, em vez de um blueprint técnico finalizado.

## ADR-01: Adotar uma arquitetura de plataforma web centrada na presença pública do negócio

- Status: Proposto
- Contexto: O repositório indica uma plataforma web moderna para um negócio local de serviços de documentação de veículos.
- Decisão: O sistema começará com uma experiência web voltada para o público, apresentando o negócio e seus serviços.
- Justificativa: Isso está alinhado com o README e apoia visibilidade online e aquisição de clientes por canais digitais.
- Consequências:
  - A arquitetura inicial deve priorizar apresentação e fluxos de geração de leads.
  - A automação completa do fluxo operacional permanece fora do escopo até que os requisitos sejam esclarecidos.
  - Detalhes como framework, hospedagem, modelo de implantação e stack são To be defined.

## ADR-02: Manter o fluxo de contato com o cliente como capacidade principal do negócio

- Status: Proposto
- Contexto: O README afirma explicitamente que a plataforma deve conectar clientes por WhatsApp e outros canais digitais.
- Decisão: O atendimento e o início do contato com o cliente serão tratados como uma capacidade central do negócio.
- Justificativa: Isso reflete a meta de transformar visibilidade do site em engajamento do cliente.
- Consequências:
  - Os mecanismos de contato devem ser desenhados cedo na implementação.
  - Fluxos de chat, formulário ou redirecionamento devem apoiar uma rota de conversão.
  - A implementação exata do canal e sua automação são To be defined.

## ADR-03: Separar a experiência pública das ferramentas operacionais internas

- Status: Proposto
- Contexto: O repositório ainda não define fluxos administrativos internos, sistemas de dados nem operações com papéis definidos.
- Decisão: A arquitetura assumirá uma separação entre conteúdo público e ferramentas futuras de gestão interna do negócio.
- Justificativa: Isso permite que o site seja projetado primeiro sem restringir prematuramente os processos operacionais.
- Consequências:
  - Conteúdo público e fluxos internos de gestão podem evoluir independentemente.
  - Capacidades administrativas do negócio permanecem To be defined.

## ADR-04: Tratar o modelo de dados e persistência como trabalho pendente de design

- Status: Pendente
- Contexto: Não há modelo de dados, requisitos de banco de dados nem contratos de integração descritos no repositório.
- Decisão: Um modelo de dados para registros de clientes, serviços, leads de contato e configuração do negócio será projetado mais tarde.
- Justificativa: O repositório atual é insuficiente para suportar um esquema final confiável.
- Consequências:
  - Tecnologia de armazenamento é To be defined.
  - Regras de manipulação de leads e dados de serviços são To be defined.
  - Requisitos de retenção e política de privacidade são To be defined.

## ADR-05: Usar um padrão de arquitetura extensível para crescimento futuro

- Status: Proposto
- Contexto: O negócio pode precisar de funcionalidades futuras, como formulários, integrações com CRM, análise e fluxos de mensagens.
- Decisão: A arquitetura deve suportar extensão modular em vez de uma implementação acoplada e rígida.
- Justificativa: Isso mantém a plataforma flexível antes que requisitos detalhados sejam finalizados.
- Consequências:
  - O desenho inicial deve favorecer limites claros entre apresentação, lógica de negócio e integrações.
  - Frameworks e fronteiras de módulos específicos são To be defined.

## Decisões Abertas

Os itens a seguir continuam sem resolução e são marcados intencionalmente como "To be defined":

- framework e stack do frontend
- linguagem ou runtime do backend
- escolha de banco de dados e esquema
- ambiente de hospedagem e implantação
- modelo de segurança e autenticação
- estratégia de analytics e rastreamento
- integrações de terceiros
- modelo de gestão de conteúdo
- modelo de papéis de administração e equipe
- abordagem de ambiente e CI/CD

## Resumo das Decisões

A direção atual da arquitetura é intencionalmente conservadora: oferecer uma presença web pública e um fluxo de contato com o cliente, enquanto adia escolhas técnicas detalhadas até que mais requisitos de negócio estejam disponíveis.

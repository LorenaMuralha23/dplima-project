# Contexto do Sistema

## Objetivo

Este projeto tem como objetivo criar uma presença digital moderna para um negócio local de serviços de despachante de veículos localizado em Petrópolis, RJ.

A plataforma deverá facilitar a descoberta do negócio por novos clientes, apresentar de forma clara os serviços oferecidos e direcionar interessados para os canais de atendimento existentes.

## Contexto de Negócio

O negócio já possui uma base de clientes recorrentes e atendimento presencial consolidado. No entanto, existe a necessidade de ampliar sua presença digital para alcançar moradores da cidade que buscam serviços de despachante pela internet.

Atualmente, grande parte do atendimento ocorre por canais diretos, principalmente WhatsApp. A plataforma busca reduzir a necessidade de contato apenas para obtenção de informações básicas, permitindo que o cliente consulte previamente serviços, valores ou faixas de preço, requisitos e formas de atendimento.

## Escopo do Sistema

Na primeira etapa, o sistema deverá oferecer uma presença digital pública para o negócio, incluindo:

- apresentação institucional do negócio;
- apresentação dos serviços oferecidos;
- exibição de informações relevantes sobre cada serviço;
- disponibilização dos canais de contato;
- direcionamento do cliente para atendimento por WhatsApp e outros canais digitais;
- apoio à descoberta do negócio por mecanismos de busca.

## Principais Atores

### Cliente / Proprietário do Veículo

Pessoa interessada em contratar um dos serviços oferecidos pelo negócio.

Principais interações:

- consultar os serviços disponíveis;
- verificar informações sobre valores, documentos e atendimento;
- acessar os canais de contato;
- iniciar uma conversa com o negócio.

### Dono do Negócio / Operador

Responsável pelo atendimento e pelas informações disponibilizadas na plataforma.

Na primeira versão, ainda não está definido se o gerenciamento dessas informações será realizado diretamente por meio de um painel administrativo ou por alterações na própria aplicação.

## Sistemas Externos e Dependências

A plataforma poderá depender de serviços externos utilizados para comunicação e presença digital, incluindo:

- WhatsApp;
- telefone;
- e-mail;
- Instagram;
- serviços de mapas e localização;
- mecanismos de busca.

Outras integrações poderão ser adicionadas conforme a evolução do projeto.

## Responsabilidades do Sistema

O sistema deverá:

1. apresentar o negócio e seus serviços de forma clara;
2. disponibilizar informações úteis para potenciais clientes;
3. facilitar a descoberta do negócio pela internet;
4. direcionar clientes para os canais de atendimento existentes;
5. reduzir a necessidade de contato apenas para esclarecimento de informações básicas;
6. servir como base para futuras funcionalidades digitais do negócio.

## Limite Arquitetural

Na primeira versão, o sistema será focado na experiência pública do cliente e na apresentação dos serviços.

Ainda não fazem parte do escopo definido:

- autenticação de usuários;
- área do cliente;
- painel administrativo;
- armazenamento de documentos de clientes;
- processamento interno de solicitações;
- automação do fluxo operacional do despachante;
- pagamentos online.

Esses recursos poderão ser avaliados futuramente conforme as necessidades do negócio.

## Perguntas Abertas

- Quais serviços são oficialmente oferecidos?
- Os preços serão fixos, exibidos como faixa de valor ou informados apenas em alguns serviços?
- Quais documentos e informações devem ser apresentados para cada serviço?
- Há necessidade de agendamento online, orçamento ou formulário de solicitação?
- Quais canais de comunicação serão disponibilizados além do WhatsApp?
- O negócio precisará de um painel para atualizar serviços e informações?
- Há necessidade de contas para funcionários ou administradores?
- Existem restrições regulatórias ou de conformidade relacionadas aos serviços apresentados?
- Quais dados, caso existam, precisarão ser persistidos?
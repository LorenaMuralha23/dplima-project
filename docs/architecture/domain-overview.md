# Visão Geral do Domínio

## 1. Escopo

Este documento apresenta um modelo inicial do domínio de um negócio local de serviços de documentação de veículos.

O modelo é intencionalmente preliminar e representa apenas os conceitos identificados até o momento. Informações e regras que ainda não foram validadas com o responsável pelo negócio permanecem como **To be defined**.

---

## 2. Conceitos Centrais do Domínio

### Negócio

Representa o estabelecimento do despachante.

Responsabilidades:

- possuir informações institucionais;
- possuir uma localização;
- possuir horários de atendimento;
- disponibilizar canais de contato;
- oferecer serviços.

---

### Serviço

Representa uma atividade ou serviço que o negócio oferece ao cliente.

Exemplos:

- transferência de veículos;
- emplacamento;
- regularização de documentação;
- pagamento ou regularização de débitos.

A lista oficial de serviços deverá ser validada com o responsável pelo negócio.

**Status:** To be defined

---

### Categoria de Serviço

Representa um possível agrupamento de serviços relacionados.

Exemplos:

- documentação;
- transferência;
- regularização.

A necessidade de utilizar categorias ainda deverá ser avaliada de acordo com a quantidade e variedade dos serviços oferecidos.

**Status:** To be defined

---

### Canal de Contato

Representa uma forma de comunicação disponibilizada pelo negócio para seus clientes.

Exemplos:

- WhatsApp;
- telefone;
- e-mail;
- Instagram.

---

### Localização

Representa o endereço físico do estabelecimento, utilizado por clientes que desejam atendimento presencial.

Pode incluir:

- endereço;
- bairro;
- cidade;
- estado;
- CEP;
- link para serviços de mapas.

---

### Horário de Atendimento

Representa os períodos em que o negócio realiza atendimento.

Pode incluir:

- dias da semana;
- horário de abertura;
- horário de fechamento;
- observações especiais.

---

### Cliente

Representa uma pessoa interessada em contratar ou obter informações sobre os serviços oferecidos pelo despachante.

Na primeira versão, o cliente não possui conta ou dados persistidos pela plataforma.

---

## 3. Relacionamentos Principais

- Um Negócio oferece vários Serviços.
- Um Serviço pode pertencer a uma Categoria de Serviço.
- Um Negócio possui um ou mais Canais de Contato.
- Um Negócio possui uma Localização.
- Um Negócio possui Horários de Atendimento.
- Um Cliente consulta Serviços.
- Um Cliente pode iniciar contato com o Negócio através de um Canal de Contato.

---

## 4. Foco do Domínio Inicial

A primeira versão da plataforma está focada principalmente em:

- apresentação do negócio;
- apresentação dos serviços;
- descoberta do negócio por potenciais clientes;
- disponibilização de informações relevantes antes do contato;
- comunicação entre cliente e negócio;
- conversão de visitantes em contatos comerciais.

---

## 5. Conceitos Fora do Domínio Inicial

Os seguintes conceitos não fazem parte da primeira versão:

- conta de usuário;
- autenticação;
- pagamento online;
- solicitação de serviço pela plataforma;
- acompanhamento de processos;
- upload de documentos;
- gerenciamento de funcionários;
- permissões;
- agendamento.

Esses conceitos poderão surgir conforme a plataforma evoluir.

A primeira versão também não contempla:

- gestão do ciclo de vida de documentos;
- automação interna de workflows;
- regras operacionais da equipe;
- integração com sistemas de processamento de terceiros;
- fluxos administrativos de aprovação.

---

## 6. Pontos em Aberto

- Quais serviços são oficialmente oferecidos?
- Os serviços serão agrupados por categorias?
- Todo serviço terá preço?
- Os preços serão fixos ou apresentados como faixa?
- Todo serviço terá prazo estimado?
- Todo serviço terá uma lista de documentos necessários?
- Haverá serviços que exigirão contato antes da apresentação de determinadas informações?
- O negócio possui apenas uma localização?
- O horário de atendimento varia de acordo com o dia?
- Existem características específicas dos serviços que precisam ser representadas no domínio?

Todos os comportamentos e regras ainda não validados permanecem como **To be defined**.
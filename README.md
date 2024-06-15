# Documentação do Projeto Interdisciplinar

## Índice

1. [Sobre o Projeto](#sobre-o-projeto)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
   - [Java](#java)
   - [HTML](#html)
   - [CSS](#css)
   - [JavaScript](#javascript)
   - [Thymeleaf](#thymeleaf)
   - [MongoDB](#mongodb)
3. [Organização do Trabalho](#organizacao-do-trabalho)
   - [Equipe](#equipe)
   - [Particionamento de Trabalho](#particionamento-de-trabalho)
4. [Impedimentos do Projeto](#impedimentos-do-projeto)
   - [Âmbito Legislativo](#ambito-legislativo)
   - [Âmbito Financeiro](#ambito-financeiro)
   - [Âmbito Técnico](#ambito-tecnico)
5. [Links Úteis](#links-uteis)
6. [Fontes](#fontes)

## Sobre o Projeto

A empresa solicitante do projeto é a WB Assessoria. O objetivo do projeto é desenvolver um facilitador que se conecta com uma API capaz de automatizar os processos de consulta da etapa de documentação, utilizando informações pessoais da pessoa imigrante. O site inclui:

- Landing page
- Suporte para múltiplas linguagens (9): Japonês, Mandarim, Português, Inglês, Árabe, Alemão, Francês, Espanhol e Africaner
- Formulário de contato
- Área administrativa com dashboard de rendimentos, processos emitidos e usuários

Por razões éticas e legislativas, as automações não foram feitas, e o sistema criado está em conformidade com a legislação vigente. O sistema permite adicionar administradores, clientes e processos, facilitando a pesquisa manual e melhorando a organização da empresa.

## Tecnologias Utilizadas

### Java

Java é uma linguagem de programação robusta, orientada a objetos, amplamente utilizada para o desenvolvimento de aplicações web.

### HTML

HTML (HyperText Markup Language) é a linguagem padrão para a criação de páginas web, estruturando o conteúdo de forma lógica e acessível.

### CSS

CSS (Cascading Style Sheets) é uma linguagem de estilo usada para descrever a apresentação de um documento escrito em HTML ou XML, permitindo a personalização de layouts, cores e fontes.

### JavaScript

JavaScript é uma linguagem de programação dinâmica que é usada principalmente para criar conteúdo interativo e dinâmico em websites.

### Thymeleaf

Thymeleaf é um motor de template Java utilizado para processar e gerar HTML, XML, JavaScript, CSS e texto plano, permitindo a integração de código Java com templates web.

### MongoDB

MongoDB é um banco de dados NoSQL orientado a documentos que armazena dados em formato JSON, facilitando a escalabilidade e a flexibilidade no gerenciamento de grandes volumes de dados.

## Organização do Trabalho

### Equipe

- **Product Owner (PO):** Guilherme Ferraz [GitHub](https://github.com/gui-zaf)
- **Scrum Master:** Marcelo Almeida [GitHub](https://github.com/marcelo-almeida-de-araujo)
- **Desenvolvedores:**
  - Lucas Barbosa [GitHub](https://github.com/TheAwesomeCake)
  - Adriano Avila [GitHub](https://github.com/Adriano2901)
  - Maria Gabriela [GitHub](https://github.com/snowtenshi)

_Guilherme Ferraz e Marcelo Almeida também participaram do processo de codificação._

### Particionamento de Trabalho

**Frontend:**

- Guilherme Ferraz
- Lucas Barbosa
- Marcelo Almeida
- Adriano Avila
- Maria Gabriela

**Backend:**

- Maria Gabriela
- Adriano Avila
- Marcelo Almeida

**Funções:**

- **Guilherme Ferraz:** Líder de Desenvolvimento Frontend, responsável pelo protótipo base do Figma, codificação de estrutura e particionamento de código.
- **Lucas Barbosa e Maria Gabriela:** Desenvolvedores das lógicas de funcionamento para modais de configuração e demais funções pertinentes.
- **Marcelo Almeida:** Líder de Desenvolvimento Backend, construtor da lógica de funcionamento e QA.
- **Adriano Avila:** Construtor de lógica de filtragem e DBA.

## Impedimentos do Projeto

### Âmbito Legislativo

As solicitações de automação da WB não foram acatadas devido a conflitos com as seguintes legislações e termos de uso do gov.br.br. Nossa equipe, no caráter ético, informou o professor orientador Marcus Vasconcelos Castro e o Coordenador do Curso Rodrigo Moura Lima Aragão sobre as solicitações da empresa:

#### Termo de Uso e Aviso de Privacidade

> **Obrigações do usuário:** O usuário é responsável pela clareza dos dados informados e pela atualização de suas informações pessoais, mantendo suas credenciais em sigilo.>

> **Responsabilidades da Administração Pública:** A Administração Pública se compromete a cumprir todas as legislações relativas ao uso correto dos dados pessoais dos cidadãos.

#### Marco Civil da Internet

**Lei 12965 - Capítulo II:**

> - "Direito à inviolabilidade da intimidade e da vida privada, sua proteção e indenização pelo dano material ou moral decorrente de sua violação."

> - "Direito à inviolabilidade e sigilo do fluxo de suas comunicações pela internet, salvo por ordem judicial."

> - "Proibição do fornecimento a terceiros de seus dados pessoais, salvo mediante consentimento livre, expresso e informado ou nas hipóteses previstas em lei."

> - "Garantia de informações claras e completas sobre coleta, uso, armazenamento, tratamento e proteção de seus dados pessoais, que somente poderão ser utilizados para finalidades que justifiquem sua coleta, não sejam vedadas pela legislação e estejam especificadas nos contratos de prestação de serviços ou em termos de uso de aplicações de internet."

**Conforme disposto na Lei nº 13.460, de 2017, são deveres do usuário do serviço:**

> - Utilização adequada dos serviços, procedendo com urbanidade e boa-fé;
> - Prestação das informações pertinentes ao serviço prestado quando solicitadas;
> - Colaboração para a adequada prestação do serviço;
> - Preservação das condições dos bens públicos por meio dos quais lhe são prestados os serviços.
>  **Ademais, são responsabilidades intrínsecas do usuário do serviço:**

> - Apresentação de informações verdadeiras e responsabilização por possíveis consequências de erros e omissões;
> - Preenchimento de dados cadastrais completos, corretos e atualizados;
> - Obediência às regras estabelecidas no termo de uso;
> - Sigilo da senha, que deve ser pessoal e intransferível;
> - Responsabilização pela segurança do dispositivo pelo qual é realizado o acesso ao serviço;
> - Reparação de danos diretos e indiretos que sejam causados à Administração Pública e a terceiros pelo mau uso do serviço.

### Âmbito Financeiro

Uma das solicitações da WB foi referente à integração de formas de pagamento e emissão de boletos ou QR code. Não acatamos a essa solicitação pois se tratam de serviços pagos e não iremos fornecer nossos dados pessoais para plataformas que oferecem tais serviços mesmo com período gratuito de teste. Além disso, não nos comprometemos a emitir QR code ou boleto, mesmo que de forma demonstrativa no nome de ninguém, uma vez que para o Banco Central se trata de uma cobrança verdadeira, mesmo que em caráter de teste.

### Âmbito Técnico

Não integramos a API do gov.br pois ela cobra por consulta e não temos opções que cumpram minimamente com o solicitado e a API do Portal da Transparência é contramão do que precisaríamos para demonstrar dados.

## Links Úteis

- [Kanban](https://github.com/orgs/fatec-project/projects/1)
- [Repositório](https://github.com/fatec-project/interdisciplinary-project-dsm3)

## Fontes

- [Termo de Uso](https://www.gov.br.br/pt-br/termos-de-uso)
- [Marco Civil da Internet](https://www.planalto.gov.br.br/ccivil_03/_ato2011-2014/2014/lei/l12965.htm)

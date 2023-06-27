# RequisicoesApp

Este projeto foi desenvolvido utilizando [Angular CLI](https://github.com/angular/angular-cli) versão 13.3.6.
E para armazenar os dados de forma segura foi optado por utilizar o Firebase.
Sistema de Armazenamento de Dados e Autenticação com Firebase.

## Introdução

Este projeto foi desenvolvido como parte do trabalho final da disciplina de Banco de Dados da faculdade. Optei por utilizar a estratégia de armazenamento de dados e autenticação utilizando o Firebase, com o objetivo de sair da zona de conforto e me desafiar a explorar tecnologias modernas e inovadoras.

## Motivação

Ao decidir sobre a abordagem para o desenvolvimento deste projeto, considerei que esta seria a última matéria de Banco de Dados em minha graduação. Em vez de seguir a abordagem convencional e decidi explorar uma solução baseada em nuvem que me permitisse aprender e aplicar conceitos de banco de dados de forma diferente.

## Firebase como Solução

O Firebase é uma plataforma de desenvolvimento de aplicativos que oferece uma variedade de serviços, incluindo armazenamento em nuvem, autenticação de usuários, notificações push e muito mais. Optei por utilizar o Firebase devido às seguintes vantagens:

1. **Facilidade de uso**: O Firebase possui uma API intuitiva e uma documentação abrangente, o que facilita o desenvolvimento e a integração do sistema.

2. **Escalabilidade**: Com o Firebase, posso aproveitar a infraestrutura e os recursos fornecidos pelo Google Cloud Platform para lidar com um grande número de usuários e garantir a escalabilidade do sistema.

3. **Armazenamento em nuvem**: Utilizando o Firebase Realtime Database ou o Firestore, posso armazenar e sincronizar facilmente os dados em tempo real, além de obter recursos avançados de consulta e filtragem.

4. **Autenticação de usuários**: O Firebase Authentication oferece uma maneira segura e fácil de autenticar os usuários do sistema, permitindo que eles acessem e interajam com os recursos disponíveis.


## Documentação de Instalação e Execução do Projeto Angular

Requisitos, ter o angular instalado na versão especificada anteriormente.
Acredito que não precise do banco de dados pois ele esta na nuvem mas estou no plano grátis(então qualquer erro so me contatar).

Agora vamos aos passos para a instalação e execução do projeto:
1. Clone o projeto:
```
$ git clone https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem.git
```

2. Instale os pacotes, pasa isso vá ao diretório da pasta client e lá execute o instal:
```
$npm install
```

3. Após isso execute o projeto:
```
$ ng serve --o
```


# Documentação de Funcionalidades

Este documento descreve as principais funcionalidades do sistema.

## Sistema de Login

O sistema possui um sistema de login que permite aos usuários autenticarem-se com suas credenciais. Ao inserir suas informações de login, o usuário terá acesso às funcionalidades do sistema.

![Tela de Login](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/43128172-df81-4429-b4ed-ccf07a78242a)


## Tela Inicial

Após o login bem-sucedido, o usuário é direcionado para uma tela inicial que dá as boas-vindas ao usuário, exibindo seu email. Essa tela inicial fornece um ponto de partida para navegar pelas funcionalidades do sistema.

![Tela Inicial](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/d73795dc-a166-4fba-a8d2-27dd5fa2540e)


## CRUD de Departamentos

O sistema possui um CRUD (Create, Read, Update, Delete) para o gerenciamento de departamentos. Os usuários com permissões adequadas podem criar, visualizar, atualizar e excluir departamentos. Essa funcionalidade permite organizar e gerenciar os diferentes departamentos da organização.

![Tela de CRUD de Departamentos](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/d503fd09-2260-43d4-95e9-d9ac0de5d118)


## CRUD de Produtos

Além do gerenciamento de departamentos, o sistema também possui um CRUD para produtos. Os usuários autorizados podem criar, visualizar, atualizar e excluir produtos. Essa funcionalidade permite um controle eficiente do estoque e informações dos produtos da organização.

![Tela de CRUD de Produtos](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/aa2a9394-d6bf-4ee6-9346-69e51cd62b5d)


## CRUD de Funcionários

O sistema oferece um CRUD para o gerenciamento de funcionários. Os usuários com as permissões adequadas podem cadastrar novos funcionários, bem como visualizar, atualizar e excluir informações de funcionários existentes. Essa funcionalidade facilita o controle e o acompanhamento dos dados dos colaboradores da organização.

### Tela de Listagem de Funcionários

![Tela de Listagem de Funcionários](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/e43a4298-f2a8-4828-b175-8edff34a91cf)


### Tela de Cadastro de Funcionários

![Tela de Cadastro de Funcionários](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/46e1df35-e101-46a8-a1c1-e192e36ce1b5)


## Requisições de Produtos

Os usuários têm a capacidade de abrir requisições para produtos específicos. Essas requisições podem ser utilizadas para solicitar novos produtos, realizar pedidos ou comunicar problemas relacionados aos produtos. A funcionalidade de requisições permite um fluxo de trabalho eficiente e uma comunicação clara entre os usuários e o departamento responsável pelo atendimento.

## Tela de Requisições

A tela de requisições exibe todas as requisições feitas no sistema. Os usuários autorizados podem visualizar as requisições de todos os departamentos.

![Tela de Requisições](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/4cbe12f8-ecb8-45c8-ae1f-3df5a0875217)

## Tela de Requisições por Departamento

A tela de requisições por departamento permite que os usuários visualizem apenas as requisições relacionadas ao departamento em que estão inseridos. Isso ajuda na organização e no gerenciamento de requisições específicas de cada departamento.
Se você reparar com atenção vai ver que uma das requisições não aparece mais

![Tela de Requisições por Departamento](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/a4a6dec6-375c-43d9-a78b-789604afda8a)


## Agora seguem algumas fotos da configuração da autenticação e do armazenamento das entidades

![Captura de tela 2023-06-26 225446](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/1ab9b263-13f2-418c-9cf1-30a7c7e91222)

![Captura de tela 2023-06-26 231552](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/1b87e0fe-2128-4be1-b410-374d99a9ebd9)

![Captura de tela 2023-06-26 225605](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/f1810a29-967a-484b-8dcc-fc3b6344dafb)

![Captura de tela 2023-06-26 225539](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/bacf311e-8a14-475d-8559-91bed2b79be9)

![Captura de tela 2023-06-26 232358](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/dea5dc19-1be7-456b-aaa1-e5de6b2341ed)


![Captura de tela 2023-06-26 225746](https://github.com/TalesReig/SistemaDeRequisicoesComBancoDeDadosNaNuvem/assets/90864593/86218484-b8b7-47aa-ad03-d02b359ec4ca)

## Conclusão

Ao escolher utilizar o Firebase para armazenamento de dados e autenticação neste projeto, busquei desafiar-me e fugir do convencional. Essa decisão permitiu-me explorar tecnologias modernas e inovadoras, enquanto adquiria habilidades relevantes para minha formação acadêmica e futura carreira. A experiência proporcionada por essa abordagem alternativa certamente contribuiu para meu crescimento como desenvolvedor de software e profissional da área de Banco de Dados.



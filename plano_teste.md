# Plano de Teste

VERSÃO: 1.0

Autor: Marcos José

Atualizado em 08/10/2023

Projeto: Nome_do_projeto

Observações:

## Introdução
Neste documento estão apenas os testes de funcionalidade para a realização do login. Em breve serão incluídos os casos de teste para outros requisitos.

## Cronograma de execução
O cronograma será definido assim que a equipe de testes for contratada.

## Casos de teste
**Localização**: Tela de Login

**Objetivo do teste**: Verificar a funcionalidade login.

**Pré-condição**: Cadastrar no sistema o usuário com login 'professor' e senha 'professor' com permissão de acesso.

**Ambiente de teste**: smartphone SO Android 10 ou superior, conectado à internet.

| **Nº** | **Procedimentos** | **Dados** | **Resultado Esperado** | **Status** |
|--------|----------------------------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| **1** | **Login correto** | | | |
| | 1. Clique no campo Usuario | | O campo deve ficar em destaque | |
| | 2. Digite o login do usuário | professor | O valor digitado deve permanecer | |
| | 3. Clique no campo Senha | | O campo deve ficar em destaque | |
| | 4. Digite a senha do usuário | professor | O valor digitado deve permanecer | |
| | 5. Clique no botão Login | | O usuário deve estar logado na tela dashboard | |
| | | | | |
| **2** | **Logout** | | | - |
| | 1. Clique no nome do usuário > "Logout" | | O usuário deve ser desconectado e redirecionado para a tela de login | |
| | | | | |
| **3** | **Login com usuário errado e senha correta** | | | |
| | 1. Digite o login no campo Usuario | prof | | |
| | 2. Digite a senha no campo Senha | professor | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. Deve aparecer uma mensagem informando "Usuário e/ou senha incorretos" | |
| | | | | |
| **4** | **Login com usuário correto e senha errada** | | | |
| | 1. Digite o login no campo Usuario | professor | | |
| | 2. Digite a senha no campo Senha | prof | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. Deve aparecer uma mensagem informando "Usuário e/ou senha incorretos" | |
| | | | | |
| **5** | **Login com usuário errado e senha errada** | | | |
| | 1. Digite o login no campo Usuario | prof | | |
| | 2. Digite a senha no campo Senha | prof | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. Deve aparecer uma mensagem informando "Usuário e/ou senha incorretos" | |
| | | | | |
| **6** | Usuario e senha sem preenchimento | | | |
| | 1. Digite o login no campo Usuario | "" | | |
| | 2. Digite a senha no campo Senha | "" | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. Os campos Usuario e Senha devem ficar com o contorno em vermelho e deve aparecer uma mensagem informando "Campo obrigatório" perto de cada um dos campos. | |
| | | | | |
| **7** | Usuário correto e senha sem preenchimento | | | |
| | 1. Digite o login no campo Usuario | professor | | |
| | 2. Digite a senha no campo Senha | "" | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. O campo Senha deve ficar destacado com o contorno em vermelho e deve aparecer uma mensagem informando "Campo obrigatório" perto o campo. | |
| | | | | |
| **8** | Usuário sem preenchimento e senha correta | | | |
| | 1. Digite o login no campo Usuario | "" | | |
| | 2. Digite a senha no campo Senha | professor | | |
| | 3. Clique no botão Login | | O usuário não recebe acesso ao conteúdo. O campo Usuario deve ficar destacado com o contorno em vermelho e deve aparecer uma mensagem informando "Campo obrigatório" perto do campo. | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |


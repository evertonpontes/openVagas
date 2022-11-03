# openVagas

## Descrição do projeto

_openVagas_ é um sistema de cadastro e divulgação de vagas de jovem aprendiz e estágios para o IFPB - Campus Pedras de Fogo. Notou-se que a divulgação de oportunidades no campus não possuia um lugar próprio para isso e foi pensando nisso que foi desenvolvido o _openVagas_. 

## Histórias de usuários

As histórias de usuários representa as funcionalidades que devem ser implementadas no sistema, além de ajudar o desenvolvedor a organizar melhor o fluxo do projeto, por onde começar e quais funcionalidades seriam mais importantes para o sistema.

**Histórias de usuário do sistema**

1. Como servidor do IFPB, gostaria de uma interface web para cadastrar vagas de estágio e jovem aprendiz.
2. Como aluno do IFPB, gostaria de um site que exibisse vagas de estágio e jovem aprendiz para que eu possa me candidatar.
3. Como aluno do IFPB, gostaria de entrar no sistema para visualizar as vagas.
4. Como aluno do IFPB, gostaria de ter uma barra de pesquisa para procurar por vagas.
5. Como aluno do IFPB, gostaria de me candidatar para ter a oportunidade de ser contratado para a vaga escolhida.
6. Como servidor do IFPB, gostaria de visualizar candidaturas para avaliar os candidatos.
7. Como aluno do IFPB, gostaria de salvar a vaga para me candidatar mais tarde.
8. Como administrador do sistema, gostaria de adicionar permissão de administrador para usuário comum.
9. Como aluno do IFPB, gostaria de receber avisos sobre as vagas.
10. Como administrador do sistema, gostaria de remover usuários indesejados.

## Quadro Scrum

O Quadro _Scrum_ é um artefato fundamental na vida do programador, pois ele exibe as histórias de usuário que devem ser implementadas no sistema e o andamento do projeto, para que assim a equipe de desenvolvedores envolvida possa se programar melhor.

[Link do Tello](https://trello.com/b/M9uyAIx6/divulga%C3%A7%C3%A3o-de-vagas-de-est%C3%A1gio-e-de-jovem-aprendiz)

## Documentação de casos de uso

Os casos de uso é um tipo de documentação que exibe o fluxo normal e as exceções de uma funcionalidade do sistema, esse tipo de documento auxilia ao programador a definir o que deve ser feito quando alguma ação não for realizada corretamente.

**Caso de uso do sistema**

### Candidatar-se para vaga
**Ator:** aluno do IFPB
**Fluxo normal:**
1. Sistema busca matrícula do aluno.
2. Aluno informa e-mail.
3. Aluno informa endereço.
4. Aluno informa motivação.
5. Sistema conclui candidatura.
6. Sistema informa que a candidatura foi realizada com sucesso.
**Extensões:**
* 1a. Se não encontrar matrícula, solicitar matrícula ao aluno.
* 1b. Se matrícula for inválida, solicitar nova matrícula.
* 2a. Se e-mail for inválido, solicitar um novo e-mail.
* 3a. Se o endereço for inválido, solicitar endereço válido.

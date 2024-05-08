### Título: Matrícula de Alunos

#### Ator Primário: Secretário(a) de Matrículas

#### Objetivo:
O objetivo deste caso de uso é permitir que o secretário(a) de matrículas registre os dados cadastrais dos alunos para realizar a matrícula.

#### Pré-condições:
- O secretário(a) de matrículas está autenticado no sistema.
- O secretário(a) de matrículas possui acesso à funcionalidade de matrícula de alunos.

#### Fluxo Principal:
1. O secretário(a) de matrículas acessa a funcionalidade de matrícula de alunos.
2. O sistema exibe um formulário de matrícula de alunos.
3. O secretário(a) de matrículas preenche os seguintes campos:
   - **Nome do Aluno**: Campo de texto para inserir o nome completo do aluno.
   - **Data de Nascimento**: Campo de texto ou seletor de data para inserir a data de nascimento do aluno.
   - **Gênero**: Seleção de gênero do aluno (masculino, feminino, outro).
   - **Endereço**: Campo de texto para inserir o endereço completo do aluno.
   - **E-mail**: Campo de texto para inserir o e-mail do aluno.
   - **Telefone**: Campo de texto para inserir o número de telefone do aluno.
   - **Curso**: Seleção do curso no qual o aluno deseja se matricular.
   - **Período**: Seleção do período de matrícula (manhã, tarde, noite).
   - **Observações**: Campo de texto opcional para inserir observações adicionais.
4. O secretário(a) de matrículas clica no botão "Enviar" para submeter o formulário.
5. O sistema valida os dados do formulário.
6. O sistema registra a matrícula do aluno e limpa os campos.
7. O sistema exibe uma mensagem de confirmação de matrícula bem-sucedida.

#### Pós-condições:
- O aluno é matriculado com sucesso e seus dados são registrados no sistema.

#### Extensões:
- Se os campos obrigatórios não forem preenchidos, o sistema exibirá mensagens de erro e não permitirá que o formulário seja submetido. O secretário(a) de matrículas deverá preencher os campos obrigatórios antes de prosseguir.

#### Fluxo Alternativo:
- Se houver problemas técnicos ou falhas durante o processo de matrícula, o sistema exibirá uma mensagem de erro e fornecerá instruções para o secretário(a) de matrículas resolver o problema ou contatar o suporte técnico.

Esta atividade de caso de uso descreve como o secretário(a) de matrículas pode usar o sistema para registrar os dados cadastrais dos alunos e realizar a matrícula com sucesso, garantindo uma experiência de usuário eficiente e sem erros. A inclusão da tabela pode ser feita para organizar visualmente os campos do formulário, mas não interfere na lógica do caso de uso em si.
# 6ENG - GRUPO 4
Projeto da matéria projeto de software. 6º Semestre Grupo 4.

# SISTEMA DE GERENCIAMENTO DE UMA LOCADORA DE VEÍCULOS-
  Nosso sistema busca facilitar o gerenciamento para empresas que trabalham com aluguel de veículos buscando implementar os requisitos básicos necessários para uma gestão organizada.

## REQUISITOS
- O sistema deverá ser iniciado pedindo "login" e "senha" do funcionário para garantir o acesso apenas para funcionários.
- O sistema deve ter gerenciamento de veículo, onde o funcionário poderá escolher a opção de castrar veículo.
- Em cadastro de veículo poderá ter as opções básicas de cadastro como cadastrar, atualizar e deletar.
- A mesma coisa se repete para clientes onde precisa ser gerenciado os clientes da empresa, cadstrando as informações do cliente.
- O sistema precisa fazer a gestão das locações cadastrando data de início, data de devolução e também o cliente e o veículo que estão nessa locação.
- O sistema tabém deverá registrar a devolução do veículo e aloca-lo novamento da frota.

## ONBOARDING PARA DESENVOLVIMENTO LOCAL
1.  `git clone https://github.com/Lukinha10/Aluguel_Carros`
2.  `cd Aluguel_Carros`
3. Instale as dependências: `npm install` (ou `yarn install`)

##  O que o Sistema Faz
O sistema realiza basicamente cadastros de clientes, veículos e aluguéis, as telas são intuitivas você deverá preencher todos os campos com os dados de preenchimento, e fazer os cadastros devidamente.

## TESTES UNITÁRIOS
- Primeiro na tela de Login será necessário utlizar um 'usuário' e 'senha', temos o objeto funcionario onde esses dois campos foram preenchidos diretamente no banco, temos o usuário que foi criado para os testes (Usuário: Lucas / Senha:12345678), qualquer outra tentativa de senha o programa não deverá abrir.
- No cadastro de locação é necessário preencher os campos de data na formatação (YYYY/MM/DD). Tente fazer o cadastro com a formatação (DD/MM/YYYY).
- Faça o cadastro de cliente, uma observação importante é que o campo 'idEndereco' não precisa ser preenchido, então faça um teste preenchendo esse campo depois faça uma segunda tentativa com o campo em branco.
- No preenchimento do endereço do cliente o número da casa não pode ser menor que 0, teste o cadastro e logo após faça um teste com o numéro menor que 0.
- Na tela de edição de dados, insira o ID do veículo desejado, por exemplo, "1". Os campos serão preenchidos automaticamente com os detalhes do veículo correspondente, permitindo edições como nome, placa, ano, marca, cor e preço de locação. Após as edições, clique em "Atualizar" para salvar as alterações no banco de dados. Para uma verificação opcional das alterações, clique em "Limpar", insira novamente o ID do veículo e clique em "Editar". Este processo simplificado proporciona uma edição intuitiva e a opção fácil de verificar as alterações no banco de dados.

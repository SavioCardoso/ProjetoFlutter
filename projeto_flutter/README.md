# projeto_flutter

Projeto em Flutter para a disciplina de Desenvolvimento de Aplicações Móveis.

## Getting Started

RoleConnect

- Tela de Login
	- email (texto)
	- senha (texto)
	- botão entrar (valida se as credenciais são válidas -> Home (Usuário/Estabelecimento))
	- botão cadastre-se (-> Tela de Cadastro)

- Tela de Cadastro
	- Usuário/Estabelecimento (Switch)
	- Cadastro de Usuário
		- Nome Completo (texto)
		- CPF (texto com máscara)
		- Data de Nascimento (Date)
		- Telefone (texto com máscara)
		- email (texto com validação)
		- confirmar email (texto com comparação)
		- senha (texto com validação)
		- confirmar senha (texto com comparação)
	- Cadastro de Estabelecimento
		- Nome do Estabelecimento (texto)
		- CNPJ (texto com máscara)
		- Telefone (texto com máscara)
		- Endereço (texto)
		- Horário de Funcionamento (texto)
		- email (texto com validação)
		- confirmar email (texto com comparação)
		- senha (texto com validação)
		- confirmar senha (texto com comparação)

- Tela Home
	- Home de Usuário
		- plota mapa na tela, com a localização atual do usuário e os estabelcimentos próximos são marcados no mapa
	- Home de Estabelecimento
		- exibe as informações do estabelecimento e permite editá-las

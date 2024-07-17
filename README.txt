Informações sobre o projeto de controle de chaves para o IFPI

Objetivo é ser um aplicativo MOBILE e para DESKTOP para ajudar o trabalho dos guardas 
das guaritas gerenciando as chaves do IFPI. Estes que têm que ficar
anotando em cadernos os horários e quem pegou as chaves, por isso, 
para facilitar esse trabalho, venho com esse projeto de aplicativo.

Junto deste arquivo, também virá um arquivo .PNG com um mapa do aplicativo para mais detalhes.

Detalhes técnicos:
o projeto deve ter 2 interfaces:

1- Login feito pelo SUAP, QR CODE ou Login manual, para que também seja 
gerenciado no histórico qual guarda estava gerenciando as chaves no momento.

2 - Tela principal, onde deve-se ver a tela dividida em 2:
	2.1 - Botão para o usuário deletar/cadastrar as chaves que serão gerenciadas,
	que poderão ser customizadas pelo nome, e posição, de acordo com a 
	vontade do usuário.
	
	Além disso, o aplicativo deve permitir o cadastro de pessoas. Uma vez cadastradas,
	elas serão automaticamente exibidas em uma lista rolável quando as chaves forem entregues
	(indicadas por retângulos verdes).
	
	Por último, um botão nomeado LOG, que deve redirecionar o usuário para uma página
	HTML com todo o histórico de entrega e horário de chaves. A escolha para HTML se
	 deve por conta da facilidade de atualizar para Coordenadores e Diretores remotamente
	sobre o histórico.
	
	2.2 - Todas as chaves cadastradas, sendo nomeadas pelo nome, com um status que se
	atualiza a cada mudança.

Configurações das chaves na interface:

Status Disponível:

Sempre de cor verde, que significa que está disponível para a entrega.
Evento quando clicado:
Aparecerá uma mini interface, que dará a lista de pessoas cadastradas (2.1)
(É necessário selecionar alguém da lista, senão, cadastre-a).
Atualização dos status para: INDISPONÍVEL
Atualização do LOG


Status Indisponível:
Sempre de cor vermelha, que significa que está sob posse de alguém.
Evento quando clicado:
Aparecer uma mini interface, mostrando a hora e quem pegou a chave,
e um botão para redefinir o status da chave para DEFINIDO.
Atualização do status para: DISPONÍVEL
Atualização do LOG





























	 
# TesteMutantVB6
Projeto avaliativo empresa Mutant

---------------------------
--- INSTRUÇÕES PARA USO ---
---------------------------

1 - Criar DB
	1.1 - Abra o SQL Server;
	1.2 - Nos arquivos do projeto, abra a pasta "SQL" e, execute o arquivo "CriaçãoDB.sql", ele irá criar o DB, a tabela e alimentá-la com usuários teste;
		1.2.1 - Valide os usuários que estão sendo inseridos nas últimas linhas do script, pois o login será feito com base em tais dados (por padrão, no script, está sendo inserido o usuário "teste" com a senha "teste".
	1.3 - Ainda na pasta "SQL", abra os demais arquivos no SQL Server e os execute. Estes são os scripts utilizados para funcionamento do projeto.

2 - Configurando o DB no Projeto
	2.1 - Através do Arquivo "DadosConexao.txt"
		2.1.1 - Abra o Arquivo "DadosConexao.txt";
		2.1.2 - Preencha todos os campos conforme especificado (Obs.: Mantenha o título e os dois pontos, atualizando somente o que consta depois).
	2.2 - Através do Código do Projeto
		2.2.1 - Abra o projeto "TesteMutant.vbp";
		2.2.2 - Abra o módulo "ModFuncoes";
		2.2.3 - Vá até a função AbreDB e altere todos os parâmetros.

3 - Utilização do projeto
	3.1 - Através do Código do Projeto
		3.1.1 - Abra o projeto "TesteMutant.vbp";
		3.1.2 - Execute o mesmo (Tecla de atalho: F5).
	3.2 - Através do Executável
		3.2.1 - Execute o arquivo TesteMutant.exe na pasta do projeto (Obs.: Caso utilizada esta opção, o arquivo "DadosConexao.txt" deve ter sido preenchido corretamente, ou as configurações do banco de dados devem ter sido alteradas conforme item 2.2 e, deve ser gerado um novo executável para utilização).

------------------------------
--- PLATAFORMAS UTILIZADAS ---
------------------------------

- Microsoft SQL Server
- Microsoft Visual Basic 6.0

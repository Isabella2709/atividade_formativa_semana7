Atualizações: •	Função para salvar lista de estudantes em um arquivo JSON.
•	Função para recuperar lista de estudantes de um arquivo JSON e armazenar em uma variável em memória.
•	Adaptação das funções de incluir, listar, excluir e editar estudantes para que acessem as duas funções acima sempre que necessário.
Tem como me dar mais detalhes?
Vamos tomar como exemplo o fluxo para incluir um estudante, a seguir o passo a passo das operações pensando nas novas funções para manipulação do arquivo JSON:
1.	Leitura dos dados do novo estudante.
2.	Criação de um dicionário ou tupla contendo todos os campos informados.
3.	Chamada à função para recuperar os dados já cadastrados.
a.	A função deve buscar o arquivo de estudantes e retornar a lista recuperada do arquivo (caso o arquivo não exista, retornar uma lista vazia).
4.	Adicionar o dicionário ou tupla na lista retornada.
5.	Chamada à função para salvar lista de estudantes atualizada.
Deste modo, sempre que incluirmos um novo estudante, já atualizaremos o arquivo que está em disco.
Bons estudos!

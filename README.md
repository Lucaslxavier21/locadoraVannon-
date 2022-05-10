# Projeto Locadora
## Como rodar o projeto;

1. Em primeiro lugar instale o .NET 6 em sua máquina caso não tenha.
2. Clone o repositório em sua máquina e utilize a sua IDE de preferência (No caso eu utilizei o Visual Studio).
3. Crie um banco de dados no SQL SERVER chamado "Locadora". 
4. Necessário trocar a "connectionString" no arquivo "appsettings.json"
5. Utilize o comando `dotnet run` para iniciar o projeto

## Como utilizar o projeto;
1. Na página inicial terá apenas o Título "Locadora", Navegue até a aba "Filmes" na parte superior da página. 
1. Cadastre um filme em sua locadora com os seguintes dados: Nome, Endereço da imagem (Copie o endereço de uma imagem do google e cole),
escolha o gênero, coloque o ano de lançamento, coloque a sinopse do filme e o tempo de duração em minutos. E salve o filme em sua locadora. 
1. Agora crie o cadastro do Cliente. Navegue até a aba Clientes - Novo cliente, e adicione os seguintes dados: Código e o Nome. 
1. Depois de ter adicionado os filmes, vá até a aba Locadora, e verá os filmes cadastrados, logo abaixo das imagens terá os botões "Detalhes" e "Alugar".
1. Clique em alugar, entre com o seu Código, clique em Alugar e pronto. Para conferir os filmes alugados, navegue até a aba "Locações".

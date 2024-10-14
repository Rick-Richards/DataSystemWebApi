# DataSystemWebApi
## Projeto desenvolvido por Richard Picolotti da Silva

#Instruções
#Para uma experiência melhor com o projeto, serão necessários realizar algumas configurações:
#1º: Após abrir a Solution, realizar o processo de Recompilação da Solution do projeto, afim de que suas referências e pacotes Nuget estejam tudo em ordem para a execução do projeto;
#2º: Feito isso, abrir o arquivo appsettings.json e alterar a ConnectionString para comunicação com o Banco de Dados
#3º: Em seguida, vai abrir o Console Gerenciador de Pacotes (Package Manager Console) que fica localizado no canto inferior do programa e seguirá os seguintes passos:
#  - Mudar o projeto padrão para DataSystemWebApiInfra afim de garantir que o projeto capture os comandos Migration por lá
#  - Executar o comando Update-Database
#  - Caso apresente erro durante a execução do comando acima, certifique-se de que o servidor do Banco de Dados SQL Server esteja ligado
#  - Caso esteja e programa ainda não conseguiu concluir o comando acima, execute o comando Remove-Migration
#  - Feito isso, vai executar o comando Add-Migration "NomeMigration" e então será criado uma nova pasta e novos arquivos do Migration
#  - Após concluído, execute novamente o comando Update-Database e então toda a estrutura do Banco de Dados será criada para a aplicação rodar
#4º: Concluído esses passos, é só executar o programa e então conferir todas as funcionalidades construídas nele.

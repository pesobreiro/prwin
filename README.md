# Polireacciómetro para Windows
## Introdução
O PsicoTest é um programa desenvolvido em C#. Esta aplicação disponibiliza um Interface com o utilizador em ambiente Windows, baseado no Windows Forms.
Foram implementadas funcionalidades baseadas nas ferramentas de desenvolvimento fornecidas no DirectX SDK, possibilitando a conexão de periféricos que são utilizados principalmente para integração de Joysticks.

Requisitos do Sistema
    - Windows NT, Windows 2000 ou Windows XP
    - Microsoft Data Access Components (MDAC) 2.7
    - Microsoft DirectX 9 Runtimes

## Descrição da Aplicação
### Ecrã Principal
Funcionalidades principais:
  - Criar testes previamente parametrizados
  - Visualizar os resultados de testes já elaborados
  - Ver o conteúdo das tabelas principais da aplicação
  - Imprimir relatórios

### Testes Parametrizados

É possível parametrizar um teste definindo cada estímulos que o teste vai ter, o que permite uma grande flexibilidade na criação de testes e na utilização de testes. Sendo também possível gravar os testes parametrizados para utilizações posteriores.
Execução do Teste

Antes de ser executado o teste é solicitado os dados do indivíduo que vai executar o teste, permitindo o seu armazenamento numa base de dados para o seu tratamento posterior.

Por outro lado, também é possível a utilização de programas de terceiros (e.g. SPSS ) para o tratamento da informação disponibilizada na Base de Dados via ODBC (Object Database Connectivity).

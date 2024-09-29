Para que o código seja executado com sucessos alguns requisitos precisam ser cumpridos. São eles:

1. Assets: Criação dos assets citados abaixo na pasta Shared do orquestrador.

Nome: GLOBAL_URL_GovFederal_ConjuntoDados
Description: URL de acesso a aba 'conjunto de dados' no site de dados do governox federal.
Conteúdo: https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj

Nome: CapturaDados_EmailsArea
Description: E-mails da área de negócio separados por ponto e vírgula.

Nome: GLOBAL_Email_Credential
Descrição: Credenciais de acesso ao e-mail

2. Permissões e acessos necessários:
-SMTP configurado para outlook
-Google chrome com extensão uipath
- Liberação do firewall ao site do governo federal


4. Bibliotecas instaladas
UiPath.Mail.Activities versão 1.21.1,
    UiPath.System.Activities versão 24.10.5,
    UiPath.Testing.Activities versão 23.10.0,
    UiPath.UIAutomation.Activities versão 23.10.8,
    UiPath.WebAPI.Activities versão 1.18.0


ATENÇÃO:
O config do processo foi confeccionado em json, evitando o uso de excel para sua leitura.


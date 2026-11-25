# Filtrar contas a receber por CPF ou CNPJ pela API

## Importante
- A listagem não tem o parâmetro **idContato**. Para filtrar pelo cliente, informe o CPF ou CNPJ em **cpfCnpj**.

## Instruções
1. Acesse **Configurações > Configurações ERP**.
2. Na seção **Outras configurações**, abra **Token API**.

   ![Lista de Configurações ERP com Token API na seção Outras configurações](screenshots/33.png)

3. Copie o valor do campo **Token**. Ele é o identificador único da conta e permite operações por API. Se o campo estiver vazio, clique em **Gerar Token API**.

   ![Tela Token API com o campo Token](screenshots/34.png)

4. Autentique a chamada com o token no formato Bearer.
5. Envie **GET /contas-receber** e informe o parâmetro opcional **cpfCnpj** com o CPF ou CNPJ do cliente. A API devolve a listagem de contas a receber filtrada por esse documento.

   ![Parâmetro cpfCnpj na listagem de contas a receber da API v3](screenshots/36.png)

## Informações adicionais
### Outros filtros da mesma listagem

Na chamada **GET /contas-receber**, estes parâmetros também são opcionais: **nomeCliente**, **situacao**, datas de emissão e vencimento, **numeroDocumento**, **numeroBanco**, **idNota**, **idVenda**, **marcadores**, **dataAtualizacao**, **orderBy**, **limit** e **offset**.

### A API v2 não filtra por CPF ou CNPJ

Na operação **Pesquisar Contas a Receber** da API v2, **token** e **formato** são obrigatórios. Informe ao menos um destes filtros: **nome_cliente**, **numero_doc**, **numero_banco**, data de emissão, data de vencimento, **situacao** (aberto, pago, cancelada, parcial) ou **id_origem**. O parâmetro **pagina** também existe. Essa pesquisa não filtra por CPF, CNPJ nem por id do contato.

![Parâmetros de Pesquisar Contas a Receber na API v2, sem CPF, CNPJ ou id do contato](screenshots/37.png)

# Integração com a Shein

## Importante
- A conexão só segue depois de **conectar com Shein**. A tela direciona para a autenticação padrão do marketplace.
- Os seletores de depósitos, naturezas de operação, formas de recebimento, categorias e variações usam o que já está cadastrado na conta.
- Com a reserva de estoque habilitada, não use o lançamento automático ao salvar o pedido. Isso invalida a reserva.
- Para importar pedidos de fulfillment, defina um depósito específico para fulfillment na configuração da integração.
- **Inativar integração**, **Excluir todos os anúncios no ERP**, **Excluir integração** e excluir variações não vinculadas são ações destrutivas.

## Instruções
### Conectar a loja

1. Acesse **Início > Integrações**.

   ![Card da Shein na página Início](screenshots/1.png)

2. Clique em **adicionar integração**.
3. Localize **Shein** na categoria Marketplace e clique em **instalar**.

   ![Catálogo com Shein Marketplace e o botão instalar](screenshots/3.png)

4. Na tela **Conectar Integração**, confira ou informe o **Nome da integração no ERP**. O campo é opcional e pode vir preenchido com Shein.

   ![Tela Conectar Integração](screenshots/4.png)

   ![Nome da integração preenchido](screenshots/5.png)

5. Leia o aviso de que você será direcionado para a autenticação padrão do marketplace. Se quiser, acesse o link **Acesse a ajuda sobre a integração**.
6. Clique em **conectar com Shein**. A autenticação do marketplace começa nesse passo. A conexão não é gravada antes dele.

### Configurar a integração

1. Em **Início > Integrações**, no card da Shein, clique em **gerenciar**.

   ![Lista de integrações com o card Shein e o link gerenciar](screenshots/2.png)

2. Na aba **Conexão**, confira o **Nome da integração no ERP** e o status conectada.

   ![Aba Conexão com status conectada](screenshots/6.png)

3. Em **Produtos**, abra **Receber Produtos**. Em **Ao importar produtos**, escolha **Importar imagens como anexos** ou **Apenas importar a URL externa das imagens**. O campo é opcional.

   ![Receber Produtos com as opções de imagens](screenshots/7.png)

4. Em **Regras de Estoque**, defina **Atualizar estoque na loja virtual**: **Não atualizar**, **Enviar saldo físico** ou **Enviar saldo disponível**. Na tabela de depósitos, selecione **Todos** ou **Próprios**. Os campos são opcionais.

   ![Regras de Estoque com atualização e depósitos](screenshots/8.png)

5. Ainda em **Regras de Estoque**, escolha **Lançamento de estoque para saídas**: **Usar configuração padrão da conta**, **Manual**, **Automático ao autorizar a nota fiscal**, **Automático ao salvar a nota fiscal**, **Automático ao salvar o pedido** ou **Automático ao marcar pedido como enviado**. Se quiser, habilite **Utilizar estoque de segurança** e informe **Estoque de segurança** com valor numérico e decimais.

   ![Lançamento das saídas e estoque de segurança](screenshots/9.png)

6. Em **Preços**, escolha a **Regra de utilização de preços**: **Preço fixo**, **Conforme lista de preços** ou **Conforme regras de preço**. Informe o **Percentual de acréscimo ou desconto** com percentual numérico e decimais. Em **Forma para aplicar valores adicionais**, escolha **Base simples** ou **Base por dentro**.

   ![Preços com regra, percentual e forma de aplicar valores](screenshots/10.png)

7. Clique em **Adicionar regra de preço e pesos**. No modal **Regra de preço e peso**, use valor fixo ou faixa de peso. No valor fixo, preencha **Preço até (regra de valor fixo)**, **Valor adicional** e **Adicional máximo** em reais. Na faixa de peso, use **Definir um limite de preço máximo** e informe **De** e **Até** em kg e **Valor do frete** em reais.

   ![Modal de valor fixo vazio](screenshots/11.png)

   ![Modal de valor fixo preenchido](screenshots/12.png)

   ![Regra por faixa de peso](screenshots/13.png)

   ![Faixa de peso preenchida](screenshots/14.png)

8. Em **Pedidos**, abra **Fluxo de Pedidos**. Ajuste **Sincronização automática de pedidos** e **Formatar nome dos contatos no recebimento dos pedidos**. Em **Completar CEP**, escolha **Não**, **Apenas se bairro não está informado** ou **Sempre**. Em **Divergência entre pagamento e valor do pedido**, escolha **Utilizar valor de pagamento integrado enviado pelo canal de venda (Recomendado)** ou **Considerar pagamento como Não integrado**. Em **Intermediador**, a opção vista é **Sem intermediador**.

   ![Fluxo de Pedidos](screenshots/15.png)

9. Em **Dados Fiscais**, escolha a **Natureza de operação para venda** entre as naturezas já cadastradas. Se quiser, habilite **Definir natureza de operação diferente para destinatários contribuintes do ICMS** e selecione a **Natureza de operação de venda para destinatários contribuintes do ICMS**.

   ![Dados Fiscais com natureza de operação](screenshots/16.png)

   ![Natureza diferente para contribuintes do ICMS](screenshots/17.png)

10. Em **Mapeamentos**, abra **Situações de Pedidos**. Use **Adicionar situações padrão** ou **Adicionar mapeamento de situação**. Em **Situação no ERP**, escolha entre **Selecione**, **Em aberto**, **Faturado**, **Cancelado**, **Aprovado**, **Preparando envio**, **Enviado**, **Entregue**, **Pronto para envio**, **Dados incompletos**, **Não entregue** e **Em devolução**. Ajuste **Permite retroceder situação dos pedidos na sincronização de situações** se precisar.

   ![Situações de Pedidos, parte superior](screenshots/18.png)

   ![Continuação do mapeamento de situações](screenshots/19.png)

11. Em **Formas de Recebimento**, habilite **Importar forma de recebimento nos pedidos** se quiser importar. Escolha a **Forma de recebimento padrão** e a **Categoria financeira padrão dos pedidos**. Clique em **Adicionar forma de recebimento** e preencha **Forma de recebimento**, **Meio de recebimento** (**Banco** ou **Gateway**) e **Código na integração**. No Banco, a conta pode ficar como **Não definida** ou usar uma conta já cadastrada.

   ![Formas de Recebimento com importação desligada](screenshots/20.png)

   ![Importação de forma de recebimento habilitada](screenshots/21.png)

   ![Linha nova de forma de recebimento](screenshots/22.png)

   ![Linha de forma de recebimento preenchida](screenshots/23.png)

12. Em **Categorias**, informe o **Código da categoria no E-commerce** na linha da categoria do ERP ou abra o ícone da categoria. No painel **Pesquisar categoria**, pesquise na árvore e clique em **atribuir categoria** ou **cancelar**.

   ![Tabela de categorias](screenshots/24.png)

   ![Painel de pesquisa de categoria](screenshots/25.png)

   ![Árvore de categorias no painel](screenshots/26.png)

13. Em **Variações**, relacione a **Variação no Sistema ERP** e a **Opção no Sistema ERP** às variações e opções recebidas do ecommerce, ou relacione os valores pelo nome.

   ![Variações com relacionar valores pelo nome](screenshots/27.png)

14. Em **Outros**, abra **Configurações Adicionais**. Em **Forma de informação da cotação do dólar**, escolha **API do Banco Central** ou **Manual**. Em **Cotação monetária do dólar**, informe o valor numérico com decimais. O link **atualizar cotação do dólar** atualiza esse valor. Em **Justificativa para atualização de preços**, escolha **Aumento no custo do produto**, **Aumento do custo logístico**, **Recomposição do preço ao final do evento** ou **Outro**.

   ![Cotação pela API do Banco Central](screenshots/28.png)

   ![Opção Manual da cotação do dólar](screenshots/29.png)

15. Em **Fulfillment**, abra **Configurações do Fulfillment**. Habilite **Importar pedidos do Fulfillment** para importar os pedidos e identificá-los com um marcador. Escolha o **Depósito do Fulfillment** e o **Lançamento de estoque para saídas de pedidos Fulfillment**, com as mesmas opções do lançamento das saídas.

   ![Configurações do Fulfillment](screenshots/30.png)

16. Clique em **Salvar**. As regras do conector ficam gravadas. A integração existente permanece com status conectada.

### Reabrir a conexão pelo card

1. Em **Início > Integrações**, localize o card da integração Shein.
2. Clique em **gerenciar**. Essa ação pode abrir a tela **Conectar Integração** em vez das abas de configuração.
3. Confira o **Nome da integração no ERP**. O campo é opcional e pode já vir preenchido.
4. Clique em **conectar com Shein** para autenticar a loja no marketplace. A autenticação não começa antes desse clique.

   ![Tela Conectar Integração reaberta pelo card](screenshots/31.png)

### Ações do card

1. Em **Início > Integrações**, no card da Shein, clique em **Ações**.
2. O menu exibe **Inativar integração**, **Excluir todos os anúncios no ERP** e **Excluir integração**. Use essas opções só quando quiser inativar ou excluir. A exclusão de anúncios só aparece para empresas em que o recurso foi liberado. Se a opção não aparecer, peça acesso ao administrador da conta.

   ![Menu Ações do card Shein](screenshots/32.png)

## Resultado
Na aba **Conexão** da integração já existente, o status exibido é conectada. O card da Shein em **Início > Integrações** oferece **gerenciar** e o menu **Ações**. A tela **Conectar Integração** mostra o nome da integração e o botão **conectar com Shein**, com o aviso de autenticação do marketplace.

## Informações adicionais
### Mapeamentos de situações já exibidos

- **Todos** corresponde a **Em aberto**.
- **Aguardando Coleta** e **Aguardando Coleta Shein** correspondem a **Preparando envio**.
- **Etiqueta Impressa** corresponde a **Pronto para envio**.
- **Entrega Confirmada** e **Sign** correspondem a **Entregue**.
- **Armazém de Entrega** corresponde a **Enviado**.
- **Reembolso** corresponde a **Cancelado**.

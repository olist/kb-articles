# Como configurar o estoque

As configurações de estoque reúnem saldo negativo, o momento do lançamento nas saídas, entradas e serviços, estorno, sincronização, lista de preços, avisos de estoque mínimo, sob encomenda e importação de inventário. No ERP da Olist, você ajusta esses parâmetros em um só lugar.

Acesse **Início > Suprimentos > Configurações > Estoque**.

> **Importante:** A conta possui reserva de estoque habilitada, que reserva estoque conforme a situação do pedido. O lançamento automático ao salvar o pedido não é recomendado, pois invalida a utilização da reserva de estoque. Desabilitar **Contratar automaticamente extensão de limite de sincronização de estoque adicional** pode bloquear a sincronização de estoque caso ultrapasse o limite do plano.

## Como acessar

1. Acesse **Início > Suprimentos > Configurações > Estoque**.
2. Revise as opções na tela **Configurações de estoque**.
3. Clique em **Salvar**, no fim da tela, para confirmar as alterações. Clique em **Cancelar** para descartar. Para somente consultar, não confirme em **Salvar**.

   ![Configurações de estoque](screenshots/1.png)

## O que cada opção faz

Nenhuma opção é obrigatória.

### Saldo negativo

- **Permite estoque negativo**: define se o estoque pode ficar negativo e, se não puder, qual saldo validar. Selecione **Sim**, **Não - Validar os saldos de todos os depósitos com saldos a considerar** ou **Não - Validar o saldo do depósito selecionado na venda**. A tela informa que não permite lançar estoque de notas fiscais, pedidos de venda e ordens de serviço se o saldo de algum produto for insuficiente.
- **Bloquear autorização de Notas Fiscais com saldo de estoque igual ou inferior a zero**: ligue para bloquear a autorização de notas fiscais com saldo físico igual ou inferior a zero. O saldo considerado é o saldo físico dos itens no depósito, conforme **Permite estoque negativo**.

### Lançamento de estoque

- **Lançamento de estoque para saídas**: define o momento do lançamento nas saídas. Selecione **Manual**, **Automático ao autorizar a nota fiscal**, **Automático ao salvar a nota fiscal**, **Automático ao salvar o pedido** ou **Automático ao marcar pedido como enviado**. A conta possui reserva de estoque habilitada. **Automático ao salvar o pedido** não é recomendado, pois invalida a utilização da reserva de estoque.
- **Lançamento de estoque para entradas**: define o momento do lançamento nas entradas. Selecione **Manual**, **Automático ao autorizar a nota fiscal**, **Automático ao salvar a nota fiscal**, **Automático ao salvar a ordem de compra** ou **Automático ao finalizar conferência de compra**.
- **Lançamento de estoque para serviços**: define o momento do lançamento nos serviços. Selecione **Manual**, **Automático ao salvar a ordem de serviço** ou **Automático ao finalizar a ordem de serviço**.

### Estorno

- **Estorno de estoques**: selecione **Manual** ou **Automático ao cancelar nota fiscal**. Ao excluir a nota fiscal, o estorno também será automático.
- **Estornar estoque automaticamente ao cancelar o pedido**: ligue para estornar o estoque automaticamente ao cancelar o pedido.

### Sincronização e lista de preços

- **Contratar automaticamente extensão de limite de sincronização de estoque adicional**: ligue para contratar automaticamente a extensão de limite de sincronização de estoque adicional. Desabilitar essa opção pode bloquear a sincronização de estoque caso ultrapasse o limite do plano.
- **Exibir estoque do produto na lista de preços**: ligue para exibir o estoque do produto na lista de preços.

### Avisos de estoque mínimo

- **Enviar e-mail sobre produtos abaixo do estoque mínimo**: ligue para enviar email sobre produtos abaixo do estoque mínimo.
- **Endereço de e-mail para receber os avisos**: digite o email que recebe os avisos.

### Sob encomenda

- **Quantidade enviada ao e-commerce quando produto sob encomenda**: informe a quantidade enviada ao ecommerce quando o produto está sob encomenda.
- **Considerar saldo em estoque no sob encomenda**: ligue para considerar o saldo em estoque na quantidade enviada ao ecommerce.

### Importação de inventário

- **Permitir editar quantidade lida na importação de inventário**: ligue para permitir editar a quantidade lida na importação de inventário.

## Perguntas frequentes

**A reserva de estoque está habilitada?**

Sim. A tela informa que a conta possui reserva de estoque habilitada e que a reserva segue a situação do pedido.

**Por que o lançamento automático ao salvar o pedido não é recomendado?**

Porque invalida a utilização da reserva de estoque.

**As opções são obrigatórias?**

Não. Nenhuma opção é obrigatória.

**O que o bloqueio de autorização de notas fiscais considera?**

O saldo físico dos itens no estoque do depósito, conforme **Permite estoque negativo**.

Quando terminar de ajustar, clique em **Salvar**. Se precisar de ajuda, fale com o suporte.

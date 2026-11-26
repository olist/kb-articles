# Como funciona a sincronização de produtos entre empresas na multiempresa

A sincronização de produtos na multiempresa liga o produto da empresa de origem ao produto da empresa de destino. Na primeira sincronização, o vínculo é de 1 para 1.

Você mantém o mesmo produto nas duas empresas. Nas sincronizações seguintes, o ERP da Olist atualiza o produto vinculado e não cria outro, mesmo que o SKU, o GTIN ou a descrição mudem na origem.

## Importante
- Se a conta de destino usa SKU sequencial, o envio é bloqueado.
- No envio manual, a mensagem é **Conta de destino possui SKU sequencial, ajuste a configuração para SKU manual para permitir o envio**.
- Na sincronização automática, você recebe uma notificação com o erro de envio. Ela leva ao relatório de sincronizações multiempresa.

## Informações adicionais
### A variação acompanha o SKU

Editar o SKU de uma variação atualiza a variação do destino, sem excluir e recriar.

### Produto excluído no destino continua vinculado

Um produto vinculado que esteja excluído no destino continua vinculado.

### Produtos já sincronizados seguem as regras anteriores

O vínculo de 1 para 1 e a atualização do produto ligado valem para os produtos sincronizados com essa lógica. Produtos que já estavam sincronizados continuam com as regras anteriores.

# Definir regras de CFOP na importação de CT-e

As regras de CFOP indicam qual código de entrada substitui o CFOP do conhecimento de transporte na importação de CT-e no ERP da Olist. Com a tabela preenchida, a importação troca o CFOP de saída pelo equivalente de entrada que você cadastrou.

Na importação manual, a aba **CT-e** oferece **Utilizar o CFOP presente no arquivo XML** ou **Substituir CFOP conforme tabela de regras de CFOP**. A segunda opção usa a tabela de regras.

## Importante
- Sem regra cadastrada, CFOP iniciado em 5 passa a 1 e iniciado em 6 passa a 2.
- Na importação de XMLs em lote de CT-e, a substituição de CFOP segue a tabela de regras do CFOP.
- O exemplo de preenchimento da tela é 5.102 em **CFOP de saída** e 1.102 em **CFOP equivalente de entrada**.

## Instruções
1. Acesse **Suprimentos > Notas de Entrada**.
2. Clique em **Importar XML** ou em **Mais ações > Importar XML**.
3. Abra a aba **CT-e**.
4. Selecione **Substituir CFOP conforme tabela de regras de CFOP**.
5. Abra a tabela de regras de CFOP.
6. Informe **CFOP de saída** e **CFOP equivalente de entrada**. Os dois campos não são obrigatórios.
7. Clique em **adicionar regra** e salve a linha.
8. Clique em **Salvar**. A importação de CT-e usa a tabela para trocar o CFOP.

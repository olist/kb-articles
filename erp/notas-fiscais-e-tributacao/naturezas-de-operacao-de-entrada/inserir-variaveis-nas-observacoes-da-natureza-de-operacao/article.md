# Inserir variáveis nas observações da natureza de operação

Nas observações da natureza de operação de entrada do ERP da Olist, você insere marcadores entre colchetes para exibir valores nas notas dessa operação. O mesmo vale para as informações ao fisco de cada aba de tributação.

O cadastro fica em **Configurações > Configurações ERP > Notas Fiscais > Naturezas de operação de entrada (tributação)**.

## Pré-requisitos
- A empresa precisa ter nota de entrada.
- Se a opção não aparecer para você, peça acesso ao administrador da conta.

## Importante
- Digite cada marcador entre colchetes, como a lista de **variáveis disponíveis** mostra.
- **Simples nacional** abre a aba **Simples**. **Regime normal** abre a aba **ICMS**.
- Nas observações do ICMS, a lista inclui [NUMERO_CUPOM] e [DATA_CUPOM]. Em **Informações ao Fisco** do ICMS, esses dois marcadores não entram.
- Em cada aba, **variáveis disponíveis** lista só os marcadores daquela aba.

## Instruções
1. Acesse **Configurações > Configurações ERP > Notas Fiscais > Naturezas de operação de entrada (tributação)**.
2. Clique em **Incluir natureza de operação**.

   ![Formulário de inclusão com observações padrões](screenshots/4.png)

   ![Lista de naturezas de operação de entrada, com pesquisa por descrição, filtro de](screenshots/1.png)

   ![Ações de linha da lista, sem alteração de dados: clonar operação, tornar padrão ](screenshots/3.png)

3. No campo **Observações padrões para notas desta operação**, clique em **variáveis disponíveis**.
4. Digite no texto os marcadores entre colchetes que devem aparecer nas notas desta operação.
5. Selecione o **Código de regime tributário** para abrir a aba **Simples** ou a aba **ICMS**.

   ![Aba Simples preenchida com dados fictícios e não salva, CSOSN 400 e CFOP ?.102.](screenshots/5.png)
6. Na aba **ICMS**, clique em **variáveis disponíveis** de **Observações do ICMS**.

   ![Aba ICMS em Regime normal, CST 00, com CFOP, alíquota, DIFAL, FCP e benefício fi](screenshots/16.png)

   ![Bloco Substituição tributária com alíquota, base, MVA/IVA, FCP, PIS e COFINS de ](screenshots/18.png)

   ![ICMS com CST 20, base 100,0000, Calcular ICMS Desonerado e Motivo da desoneração](screenshots/19.png)

   ![ICMS com CST 51, percentual de diferimento, alíquota FCP e percentual de FCP dif](screenshots/20.png)

   ![ICMS com CST 60 e campos de alíquota e base de ICMS efetivo.](screenshots/21.png)

   ![CST 60 com a caixa Obter ICMS-ST retido anteriormente a partir de nota fiscal de](screenshots/22.png)
7. Digite, com colchetes: [VALOR_BASE_ICMS], [VALOR_BASE_DIFERIMENTO], [VALOR_DIFERIMENTO], [VALOR_CREDITO_ICMS], [ICMS_PRESUMIDO], [ALIQUOTA_CREDITO_ICMS], [VALOR_ICMS_DESONERADO], [NUMERO_CUPOM] e [DATA_CUPOM].

   ![Lista de variáveis das observações do ICMS](screenshots/23.png)

   ![Aba IPI com CST 03 Entrada não-tributada, alíquota 0 e código de enquadramento 9](screenshots/6.png)

   ![Aba ISSQN com situação isento, alíquota 0, base 100 e Descontar ISS Não, sem sal](screenshots/7.png)

   ![Aba PIS com CST 01, alíquota 0 e base 100, sem salvar.](screenshots/8.png)

   ![Aba COFINS com CST 01, alíquota 0 e base 100, sem salvar.](screenshots/9.png)

   ![Aba Importação com situação Não tributado e alíquota 0, sem salvar.](screenshots/10.png)

8. Em **Informações ao Fisco** do ICMS, clique em **variáveis disponíveis**.

   ![Painel Exceções do II vazio, com Qualquer estado, produtos, origens 0 a 8, NCMs ](screenshots/12.png)

   ![Inclusão de produto na exceção, com linha de SKU ainda não salva.](screenshots/13.png)

   ![Inclusão de NCM na exceção, com a linha ainda não salva.](screenshots/14.png)

   ![Aviso ao avançar a exceção sem regra válida: não foi possível salvar o cadastro ](screenshots/15.png)
9. Digite, com colchetes: [VALOR_BASE_ICMS], [VALOR_BASE_DIFERIMENTO], [VALOR_DIFERIMENTO], [VALOR_CREDITO_ICMS], [ICMS_PRESUMIDO], [ALIQUOTA_CREDITO_ICMS] e [VALOR_ICMS_DESONERADO].

   ![Lista de variáveis das informações ao fisco do ICMS](screenshots/24.png)

   ![Configurações avançadas expandidas: preço considerado, CMV, produtor rural, esto](screenshots/11.png)

10. Nas abas **Simples**, **IPI**, **ISSQN**, **PIS**, **COFINS** e **Importação**, clique em **variáveis disponíveis** e digite os marcadores daquela aba entre colchetes em **Observações** e em **Informações ao Fisco**.
11. Clique em **Salvar**. O ERP grava a natureza com os textos e os marcadores.

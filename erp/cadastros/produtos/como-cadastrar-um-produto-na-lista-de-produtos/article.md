# Como cadastrar um produto na lista de produtos

## Descrição

A lista de produtos do ERP da Olist permite cadastrar os itens que você vende e consultá-los por descrição, código (SKU), unidade, preço e estoque.

Acesse a lista em **Cadastros > Produtos**. Você pode cadastrar pela tela, em **Incluir produto**, ou importar por planilha, em **Mais ações > Importar produtos de uma planilha**.

## Pré-requisitos

- Acesso à lista de produtos, com **Cadastros** visível no menu lateral do ERP.
- Para importar por planilha, permissão de produtos, permissão de importação de registros e permissão para incluir e editar produtos.
- Arquivo Excel (.xls ou.xlsx) ou texto (.csv), de no máximo 2 Mb, preenchido a partir da planilha modelo.

## Importante

- Para emitir nota fiscal, preencha **Origem do produto conforme ICMS** e **Unidade de medida**.
- Nenhum campo da aba **Dados Gerais** é obrigatório.

## Instruções

### Pela tela

1. Acesse **Cadastros > Produtos**.
2. Clique em **Incluir produto**.
3. Preencha a aba **Dados Gerais** de **Novo produto**. O formulário também tem as abas **Dados Complementares**, **Ficha técnica**, **Anúncios**, **Preços**, **Custos** e **Outros**.

#### Identificação do produto

- **Tipo do Produto**: opções **Simples**, **Kit**, **Com variações**, **Fabricado** e **Matéria-prima**. O padrão é **Simples**.
- **Nome do produto**
- **Código de barras (GTIN)**
- **Código (SKU)**

#### Dados fiscais

- **Origem do produto conforme ICMS**: necessário para emitir nota fiscal. O padrão é **0 - Nacional, exceto as indicadas nos códigos 3 a 5**. Há opções de 0 a 8 para origem nacional ou estrangeira e faixas de conteúdo de importação.
- **Unidade de medida**: necessário para emitir nota fiscal.
- **NCM - Nomenclatura comum do Mercosul**: o campo tem o botão **sugerir o ncm**.
- **Código CEST**: código especificador da substituição tributária.

#### Preços e peso

- **Preço de venda**
- **Preço promocional**
- **Peso Líquido**
- **Peso Bruto**

#### Embalagem

- **Tipo da embalagem**: opções **Envelope**, **Pacote / Caixa** e **Rolo / Cilindro**. O padrão é **Pacote / Caixa**.
- **Embalagem**: o padrão é **Embalagem customizada**. A lista também oferece caixas de encomenda, inclusive Flex, CE e variações de tamanho.
- **Largura**
- **Altura**
- **Comprimento**
- **Peso da embalagem**

#### Estoque

- **Controlar estoque**: acompanhamento da movimentação de estoque. Opções **Sim** e **Não**. O padrão é **Sim**.
- **Estoque inicial ( E-commerce )**
- **Estoque mínimo**
- **Estoque máximo**
- **Sob encomenda**: opções **Sim** e **Não**. O padrão é **Não**.
- **Controlar lotes**: opções **Sim** e **Não**. O padrão é **Não**.
- **Localização**: localização física no estoque.
- **Dias para preparação**

![Formulário Novo produto na aba Dados Gerais](screenshots/3.png)

Se não quiser gravar, clique em **Cancelar**. O preenchimento é descartado e você volta à lista de produtos.

4. Clique em **Salvar**.

### Por planilha

1. Acesse **Cadastros > Produtos**.
2. Clique em **Mais ações > Importar produtos de uma planilha**.
3. Na tela **Importação de produtos via planilha**, no passo 1, clique em **baixar planilha**.
4. Preencha a planilha modelo com os produtos.
   - Mantenha a mesma quantidade de colunas do modelo de importação.
   - Informe cada nível de variação como tipo e valor separados por dois-pontos, com no máximo 5 níveis separados por duas barras verticais (||).
   - A variação só é vinculada ao produto pai se ele já estiver cadastrado com o **Código (SKU)** informado.
   - O estoque não é atualizado para kits nem para produtos do tipo variações.
   - O fornecedor só é vinculado ao produto se já existir um contato cadastrado com o mesmo nome.
   - O **Preço promocional** só é importado quando a empresa possui o módulo de preço promocional.
5. Consulte **Orientações** na mesma tela.
6. Se precisar, acesse o link **Dicas para preencher corretamente** e leia as perguntas frequentes da mesma tela.
7. No passo 2, clique em **enviar planilha** e envie o arquivo Excel (.xls ou.xlsx) ou texto (.csv), de no máximo 2 Mb.

## Informações adicionais

### O produto pode ser criado e atualizado por estes canais

- Interface/Tela: criar sim, atualizar sim
- Lote (Planilha): criar sim, atualizar sim
- API V3: criar sim, atualizar sim
- Lis: criar sim, atualizar sim

## Links relacionados

Se precisar de ajuda para cadastrar o produto, fale com o suporte.

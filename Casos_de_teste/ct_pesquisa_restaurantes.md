# Casos de Teste - Pesquisa de Restaurantes

## CT-002 - Fazer busca na barra de pesquisa

**Pré-condições:**  
- Estar na página inicial.  
- Estar com endereço inserido.  

**Dados de Entrada:** Restaurante  

**Passos:**  
1. Acessar página inicial da Web.  
2. Clicar na barra de pesquisa.  
3. Inserir "Restaurante" na barra de pesquisa.  
4. Apertar "Enter" no teclado.  
5. Verificar informações de restaurantes.  

**Resultado Esperado:**  
- Visualização de Restaurantes de acordo com a pesquisa.  
- Visualização de informações dos Restaurantes como: Estrelas, tipo, distância e frete.  

**Prioridade:** Alto

**Resultados do teste**
**Status:** Sucesso
**Descrição:** O sistema se comportou como esperado.
**Observações:** Todos os passos foram executados com êxito. 

**evidências:** 
![CT-002_busca_restaurante.gif](../evidencias/pesquisa_restaurantes/CT-002_busca_restaurante.gif)

---

## CT-003 - Verificação de rolagem da página

**Pré-condições:**  
- Estar na página inicial.  
- Estar com endereço inserido.  

**Passos:**  
1. Pesquisar restaurante.  
2. Verificar informações dos restaurantes.  
3. Descer página com scroll do mouse ou barra de rolagem.  
4. Clicar em "ver mais".  

**Resultado Esperado:**  
- Visualização de itens relacionados à pesquisa.  
- Após carregar mais de 100 itens aparece opção de "ver mais".  
- Ao clicar em "ver mais", novos restaurantes são carregados.  

**Prioridade:** Médio

**Resultados do teste**
**Status:** sucesso
**Descrição:** O sistema se comportou como esperado.
**Observações:** Todos os passos foram executados com êxito. 

**evidências:** 
![CT-003_rolagem_pagina.gif](../evidencias/pesquisa_restaurantes/CT-003_rolagem_pagina.gif)

---

## CT-005 - Verificar busca por itens

**Pré-condições:** Estar na página inicial.  
**Dados de Entrada:** Hamburguer  

**Passos:**  
1. Acessar página inicial da Web.  
2. Navegar até barra de pesquisa.  
3. Inserir dados de entrada.  
4. Apertar "Enter".  
5. Clicar em "itens" ao lado de "lojas".  
6. Navegar por itens carregados.  

**Resultado Esperado:**  
- Visualização de itens correspondentes aos dados de entrada.  
- Informações dos itens como: Restaurante, Nome, Valor, Frete, Estrelas, Distância e Tempo previsto.  

**Prioridade:** Médio

**Resultados do teste**
**Status:** sucesso
**Descrição:** O sistema se comportou como esperado.
**Observações:** Todos os passos foram executados com êxito. 

**evidências:** 
![CT-005_busca_itens.gif](../evidencias/pesquisa_restaurantes/CT-005_busca_itens.gif)

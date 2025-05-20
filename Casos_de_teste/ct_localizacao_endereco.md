# Casos de Teste - Localização e Endereço

## CT-001 - Adicionar e verificar endereço

**Pré-condição:** Estar na página inicial.  
**Dados de Entrada:**  
- Endereço válido: Brasília-DF  
- Ponto de referência: Parque da cidade  

**Passos:**  
1. Acessar pagina inicial da Web.  
2. Clicar no botão "Ver mercados próximos".  
3. Adicionar endereço válido.  
4. Clicar em confirmar localização.  
5. Adicionar ponto de referência.  
6. Clicar em "Salvar endereço".  

**Resultado Esperado:**  
- Endereço salvo com sucesso.  
- Liberação da barra de pesquisa de item ou loja.  

**Prioridade:** Alto

**Resultados do teste**
**Status:** Sucesso
**Descrição:** O sistema se comportou como esperado.
**Observações:** Todos os passos foram executados com êxito. 

**evidências:** 
![CT-001_adicionar_endereco.gif](../evidencias/localizacao_endereco/CT-001_adicionar_endereco.gif)

---

## CT-004 - Verificar interação com botões relacionados à funcionalidade de localização

**Pré-condição:** Estar na página inicial.  
**Dados de Entrada:**  
- Endereço válido: Brasília-DF  
- Ponto de referência: Parque da cidade  

**Passos:**  
1. Acessar página inicial da Web.  
2. Navegar até endereço.  
3. Testar botão seta à esquerda de "voltar".  
4. Navegar até "usar minha localização".  
5. Clicar em "permitir".  
6. Clicar em "entrar ou cadastrar".  

**Resultado Esperado:**  
- Teste de botões de voltar, localização, entrar ou cadastrar e permitir com sucesso.  

**Prioridade:** Médio

**Resultados do teste**
**Status:** Falha
**Descrição:** Mesmo com a geolocalização ativada e permissões de localização permitidas no navegador no "Você precisa ativar a geolocalização para utilizar essa funcionalidade ".
**Observações:** Todos os passos foram executados porém sem êxito.

**Reprodução:** 
1. Verifique se a geolocaliação de sistema e permissão do navegar estão ativas.
2. Acesse o site e Clique em "Usar minha localização".
3. Observe que o erro mesmo com as permissões ativadas corretamente.

**evidências:** 
![CT-004_botos_localizacao.gif](../evidencias/localizacao_endereco/CT-004_botoes_localizacao.gif)

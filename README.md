# **READ.ME**

### Este repositório contém um script Python para realizar análises e manipulações de dados relacionados a lojas, PIB e população de municípios brasileiros. Abaixo estão listadas as etapas realizadas pelo script:


1. **Lendo e tratando a planilha de lojas:**
   - O script lê os arquivos de Excel contendo informações sobre lojas, PIB e população de municípios.

2. **Juntando PIB e população em uma única planilha de acordo com a cidade:**
   - Os dados de PIB e população são mesclados com base no nome da cidade.

3. **Calculando o PIB per capita e criando a coluna correspondente:**
   - E calculado o PIB per capita com duas casas decimais e adicionada uma nova coluna com esse valor.

4. **Separando UF (Unidade Federativa) da cidade:**
   - Os nomes das cidades são ajustados para separar o nome da cidade do nome da UF.

5. **Renomeando colunas das planilhas:**
   - As colunas das planilhas são renomeadas para facilitar o merge posterior.

6. **Removendo espaços em branco das strings:**
   - Espaços em branco são removidos das strings para evitar erros durante o processo de junção dos dados.

7. **Criando a planilha onde PIB e população se juntarão à planilha de lojas:**
   - As planilhas são mescladas com base no nome da cidade.

8. **Removendo coluna adicional "UF" resultante da junção:**
   - Uma coluna adicional "UF" é removida da planilha resultante.

9. **Salvando o resultado em um novo arquivo Excel:**
   - O resultado final é salvo em um novo arquivo Excel.

10. **Filtrando municípios para lojas com potenciais e com base em critérios específicos:**
    - São filtrados os municípios com população superior a 150.000 habitantes e PIB per capita acima de 50.

Para utilizar o script, certifique-se de ter as bibliotecas pandas instaladas e os arquivos de Excel com os dados correspondentes. Após a execução do script, você terá uma planilha contendo as informações das lojas, PIB, população e PIB per capita dos municípios, além de uma filtragem específica dos municípios para lojas.

Para mais detalhes sobre as etapas e o funcionamento do script, consulte o código-fonte fornecido neste repositório.

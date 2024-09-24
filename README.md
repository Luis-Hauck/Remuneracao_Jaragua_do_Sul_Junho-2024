# Análise Exploratória das Remunerações da Prefeitura de Jaraguá do Sul - Junho/2024

**Descrição:**
Este repositório contém o código e os resultados de uma análise exploratória dos dados da remunerações dos servidores públicos da Prefeitura de Jaraguá do Sul, referente ao mês de junho de 2024. O objetivo principal é identificar padrões, discrepâncias e gerar insights sobre a estrutura salarial da prefeitura.

**Tecnologias Utilizadas:**
* Python
* Pandas
* Matplotlib


**Dados:**
Os dados utilizados foram obtidos de https://transparencia.betha.cloud/#/eGpEZiz7rOS-yefKWGP5Gg==/consulta/8768.
Vale ressaltar que filtrei somenete as pessoas que trabalhavam efetivamente, excluindo pensionistas, aposentados etc...
Além disso o arquivo em xlsx foi tratado para retirar inforamações pessoais delicadas como nome,.


**Análise:**
Foram realizadas as seguintes análises com base no dados:
* Os cargos comissionados representa quantos % da remuneração total?
* Qual a diferença da remuneração média entre cargos comissionados e efetivos?
* Quais os cargos mais ocupados?
* Quais as a entidade com maior média de remuneração bruta? E qual teve o maior gasto com remuneração?


**Resultados:**
* Os cargos comissinados representaram 10% da remuneração em junho sendo que os mesmos só representaram 6% dos funcionários.
* A diferença entre cargos comissionados foi de quase 32%.
* Os cargos mais ocupados foram de professores.
* A maior entidade com maior remuneração média foi a FUJAMA, mas a maior entidade com gastos foia prefeitura

**Observações**
Vale ressaltar que nessa análise específica os dados não foram tratados, justamnete para encontrarmos os outliers(ex: algumas pessoas ganharam as ferias e o 13 adiantado), além disso podemos perceber que existem remunerações zeradas por serem estágios não remunerados.
Faço a análise completa em um dos vídeos do meu canal: https://www.youtube.com/live/-hNWhaBFDGM

**Contribuições:**
Contribuições são bem-vindas! Abra um pull request para propor mudanças.

**Licença:**
Este projeto está licenciado sob a MIT License.

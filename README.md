# 6-Performance-Vendedores-PowerBI
Painel interativo com a performance de uma equipe de vendas.

# As perguntas de Negócio / Solicitações do CEO:

1) Me faça um **KPI dinâmico** para eu avaliar metas para o total vendido.
   Quero poder variar entre **$ 10.000 e $ 2.000.000 com intervalos de $50.000.**

<br>

2) Eu quero um Funil com as TOP 15 cidades de vendedores que mais pagam frete.

<br>

3) Faça uma tabela que **condicione** as análises para valores de frete.
   Obs.: faça **Frete > $ 25.000 e Valores de frete**

<br>

4) Crie um mapa com layout diferente que eu possa navegar por **País**, **Estado** e **Cidade** através do total vendido.

<br>

5) Me traga quantos vendedores estão **dentro ou acima da meta de total vendido**. Quero **manipular os valores** das metas de total vendido de forma **dinâmica na tela.**

##  Medidas DAX

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/6d5ad201-c95f-4f4e-8800-afb72db8a535" />
</div>

## Respondendo a 1º solicitação do CEO:

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/316949f8-b640-4771-8811-a918a9469589" />
</div>

<br>
<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/4e3a73b6-1906-4e37-ad38-906efca993a7" />
</div>

<br>

### Meta Variavel:
   *Permite que o CEO ajuste de acordo com a meta que ele queira ver, tornando uma visualização dinamica em tempo real.*

## Respondendo a 3º solicitação do CEO:

<div align="center">
<img src="https://github.com/user-attachments/assets/05fd9b33-cc5c-4a46-828b-9e97b1d3b318" />
</div>

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/38144eb3-8906-4640-8c4b-008fa9786b1e" />
</div>

<br>

## Respondendo a 5º solicitação do CEO:

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/321f8896-569f-4ddd-9f75-83dbb0c5275a" />
</div>

<br>

### Função Filter:
   *Retorna uma tabela que representa um subconjunto de outra tabela ou expressão.*

### Função Values:
   *Quando o parâmetro de entrada é um nome de coluna, retorna uma tabela de uma coluna que contém os valores distintos da coluna especificada.*
   *Valores duplicados são removidos e apenas valores exclusivos são retornados.*

<br>

---

# Dashboard

<br>

<div align="center">
<img src="https://github.com/user-attachments/assets/718f2dbb-c214-4b71-9847-0ee79961aa9f" />
</div>


# preditct_h1n1_flu_shot
 
O atual projeto, com fins puramente acadêmicos, é um desafio do site DrivenData (https://www.drivendata.org/competitions/66/flu-shot-learning/) e a proposta é desenvolver 2 modelos de predição:

<li>um modelo de predição para identificar pessoas propensas a tomar a vacina do H1N1;</li>
<li>um modelo de predição para identificar pessoas propensas a tomar a vacina da gripe.</li>

O case foi resolvido de duas formas diferentes, uma em linguagem R e outra em Python.

<b>Em R</b>
<br>
O ajuste do modelo de regressão logística foi realizado através da distribuição Binomial:
<li>cada indivíduo pode assumir 2 valores (tomar ou não a vacina);</li>
<li>o experimento é uma tentativa de N tentativas idênticas;</li>
<li>cada tentativa é uma Bernoulli;</li>
<li>a probabilidade de tomar ou não a vacina não muda de tentativa para tentativa;</li>
<li>as tentativas são independentes entre si.</li>

<br>

<b>Em Python</b>
<br>
Foram ajustados diversos modelos utilizando o pipeline, e bibliotecas de feature engineering para facilitar e otimizar o processo. O modelo campeão foi <b>Catboost</b>.

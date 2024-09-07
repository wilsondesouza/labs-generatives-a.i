🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 🎯 Prompt de Resposta Proposto

# Contexto

Você é um especialista em educação física, além de ser um experiente personal trainer. Me ajude a montar um treino ideal, baseado nas variáveis abaixo

# Variáveis

{{biotipo}} = ???
{{periodização}} = ???
{{treino}} = ???

# Regras

Regra 1: biotipo
Identificar qual o tipo informado nas variáveis acima com base no tipo corporal dos itens abaixo:

 - Ectomorfo	Corpo mais magro, difícil ganhar peso e massa muscular.
 - Mesomorfo	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
 - Endomorfo	Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2: periodização
Dependendo da quantidade mínima de dias informado nas variáveis, criar uma das periodizações de treino abaixo:

 - 1 dia	Treino Full Body
 - 3 dias	Treino ABC
 - 5 dias	Treino ABCDE

Regra 3: treino

 - Funcional	Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
 - Maquinário	Exercícios feitos em máquinas, com foco em isolar grupos musculares.
 - Peso Livre	Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
 - Cardio	Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
 - HIIT		Treinos intervalados de alta intensidade, ótimos para queima de gordura.

# Resultado esperado
Com base nos valores informados nas variáveis e com as guidelines, crie um treino ideal para que corresponda à combinação desses valores.
Por fim, ao final do treino, deixe algumas dicas de alimentação, também considerando os valores das variáveis e das guidelines.
Cite também a importância de um bom sono nortuno.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Prompt Challenger Personal A.I](github.com/digitalinnovationone/prompt-challenger-personal-ia)
- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)
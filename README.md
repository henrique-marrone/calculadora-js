📟 Calculadora JavaScript

Calculadora web desenvolvida em HTML, CSS e JavaScript puro, utilizando um motor matemático próprio (sem eval) para realizar os cálculos com segurança, precisão e comportamento realista de calculadora.

O projeto foi criado com foco em lógica, parsing matemático e experiência do usuário, e não apenas em interface.


🔗 Demo
👉 https://henrique-marrone.github.io/calculadora-js/


🚀 Funcionalidades

Operações básicas: + − × ÷

Suporte a vírgula decimal (padrão PT-BR)

Porcentagem absoluta e relativa (estilo calculadoras HP)

Ordem correta das operações (precedência matemática)

Suporte a parênteses

Botão de apagar (⌫) e limpar (C)

Interface responsiva e moderna


🧮 Exemplos
Expressão	Resultado
10%	0,1
50+10%	55
200-25%	150
100*(5+10%)	115
10,5+2,3	12,8


🧠 Como funciona

Ao invés de usar eval(), a calculadora possui um parser matemático próprio, que executa os seguintes passos:

Converte vírgula para ponto

Converte porcentagens (%) em expressões matemáticas

Resolve parênteses de forma recursiva

Aplica precedência matemática (× ÷ antes de + −)

Executa as operações

Converte o resultado final para vírgula

Isso garante segurança, previsibilidade e comportamento real de calculadora física.


🛠️ Tecnologias utilizadas
HTML5
CSS3
JavaScript 


👤 Autor
Henrique Takahashi
Projeto desenvolvido como parte de estudos em desenvolvimento web, lógica e construção de engines matemáticas em JavaScript.


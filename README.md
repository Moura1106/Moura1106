# Olá! 👋

Estudante de tecnologia em busca de oportunidades na área de TI. Gosto de transformar um problema do dia a dia
em um sistema que funciona: modelar, programar, testar e documentar.

Os projetos abaixo usam **dados fictícios** e rodam no seu computador (cada repositório tem um
`iniciar_demo.bat` e prints no README).

## Projetos

### [pastelaria](https://github.com/Moura1106/pastelaria): controle financeiro de um pequeno negócio
Sistema web para registrar despesas e receitas, importar o extrato da maquininha (CSV do Mercado Pago),
acompanhar parcelas e ver o resultado do mês. Inclui um assistente com IA (API da Anthropic) que responde
perguntas sobre os dados usando ferramentas somente de leitura.
`Python` `Flask` `SQLAlchemy` `SQLite` `pytest` `Anthropic API` · 96 testes

### [rankedu](https://github.com/Moura1106/rankedu): ranking de cursos de faculdades
Projeto acadêmico, combina a nota oficial do MEC (CPC/ENADE) com a avaliação de empresários, com
moderação por administrador. A modelagem UML veio antes do código, e as regras de negócio estão no código e
no banco.
`Python` `Flask` `SQLite (SQL puro)` `Jinja2` `pytest` · 34 testes

### [dashboard-interativo](https://github.com/Moura1106/dashboard-interativo): Dashboard de repasse a locadores
em um ambiente de imobiliária, gerado a partir de uma planilha mensal: pagos, a vencer, vencidos, valores
repassados e taxa de administração. Gráficos feitos à mão em SVG, com tema claro e escuro.
`Python` `openpyxl` `JavaScript` `SVG` `pytest` · 7 testes

## Tecnologias

`Python` · `Flask` · `SQLAlchemy` · `SQLite` · `JavaScript` · `HTML/CSS` · `pytest` · `Git/GitHub` · `UML`

## Como costumo trabalhar

- Regras de negócio com testes automatizados.
- README com passo a passo testado a partir de um clone limpo.
- Nenhum dado real nos repositórios: dados de exemplo gerados por script.

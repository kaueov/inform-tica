# inform-tica
repositório para tarefas de info;
Membros; Kauê Venancio e  Pedro Hernandes;

# TABELA DE EXAMES LABORATORIAIS REALIZADO NO HOSPITAL DAS CLINICAS DE RIBEIRÃO PRETO - SP;

##
Fonte de dados: http://catalogo.governoaberto.sp.gov.br/dataset/274-exames-laboratoriais/resource/e24cf0ee-1cd5-41ce-97b3-fcd89ed103cb
## Perguntas
1- Qual laboratório mais se repete na tabela? \
2- Quantos procedimentos cada laboratório fez no total? \
3 - Qual a quantidade total de cada procedimento feito no total? \
4- Quantos de cada procedimento foram feitos no laboratório UNESP? \
5- Independente do ano, quantos procedimentos foram feitos em cada mês?\

## Formulas Usadas:
1=CONT.SE('coluna de laboratorios';'nome do laboratório') \
2=SOMASE('coluna de laboratorios';'laboratório';'coluna de quantidade de procedimentos') \
3=SOMASE('coluna de procedimentos';'procedimento';'coluna de quantidade de procedimentos') \
4=SOMASE('coluna de procedimentos';'procedimento';'coluna de quantidade de procedimentos') \
5=SOMASE('coluna de meses';'mes';'coluna de quantidade de procedimentos') 

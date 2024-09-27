# inform-tica
repositório para tarefas de info
### Membros
Kauê Venancio e  Pedro Hernandes

# TABELA DE EXAMES LABORATORIAIS REALIZADO NO HOSPITAL DAS CLINICAS DE RIBEIRÃO PRETO - SP;

##
Fonte de dados: http://catalogo.governoaberto.sp.gov.br/dataset/274-exames-laboratoriais/resource/e24cf0ee-1cd5-41ce-97b3-fcd89ed103cb
## Perguntas
1- Qual laboratório mais se repete na tabela? \
2- Quantos procedimentos cada laboratório fez no total? \
3 - Qual a quantidade total de cada procedimento feito no total? \
4- Quantos tipos procedimentos foram feitos no laboratório UNESP? \
5- Independente do ano, quantos procedimentos foram feitos em cada mês?\

## Formulas Usadas:
1=CONT.SE('coluna de laboratorios';'nome do laboratório') \
2=SOMASE('coluna de laboratorios';'laboratório';'coluna de quantidade de procedimentos') \
3=SOMASE('coluna de procedimentos';'procedimento';'coluna de quantidade de procedimentos') \
4=SOMASE('coluna de procedimentos';'procedimento';'coluna de quantidade de procedimentos') \
5=SOMASE('coluna de meses';'mes';'coluna de quantidade de procedimentos') 


## Gráficos
![image](https://github.com/user-attachments/assets/39440398-28c0-4513-af13-0a0249616062)


![image](https://github.com/user-attachments/assets/95b2179c-a9df-469c-914a-d4321e380b9e)


![image](https://github.com/user-attachments/assets/ff06498d-ad25-4228-9ddb-ac7617adb7d8)


![image](https://github.com/user-attachments/assets/43bae17e-e39e-42f7-829d-db92c510f2b3)


![image](https://github.com/user-attachments/assets/42af0935-42cd-47d2-8104-17238a9cdc73)

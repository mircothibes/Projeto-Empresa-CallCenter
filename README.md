Projeto de Análise de Dados para uma Empresa de Call Center + Deploy Google CLoud Platform

Este é um projeto de análise de dados desenvolvido para uma empresa de call center. 

O objetivo principal é criar um dashboard interativo para visualização dos dados tratados e analisados, 
permitindo a filtragem dos gráficos por meses e equipes.

O dataset utilizado neste projeto está em formato .csv e foi processado no Jupyter Notebook utilizando técnicas de análise, 
tratamento/modelagem e plotagem de dados em vários formatos de gráficos. O projeto final com o dashboard foi desenvolvido no VSCode.

O projeto também inclui uma apresentação em PowerPoint para facilitar a compreensão de cada gráfico e 10 sugestões de melhorias para a empresa.


Utilizando apenas PYTHON e as bibliotecas:

- Dash
- Dash-Core-Components
- Dash HTML
- Dash Bootstrap
- Plotly
- Pandas



O Projeto também conta com o deploy para o Google Cloud Platform.

#
![image](https://github.com/mircothibes/Projeto-Empresa-CallCenter/assets/120477644/85757f4e-0708-46c3-9d07-f75c042b20c0)


  
  
Foram criados mais 3 arquivos dentro do projeto para o deploy
- requirements.txt
Neste arquivo fora listadas todas as bibliotecas que o projeto necessitou, nomes e versões.
    
- Dockerfile
Neste arquivo foi criado um conteiner em docker com o projeto mais o requirements.
    
- README.md
Neste aqruivo estão os dois comandos para o deploy, nestes comandos está o numero de ID do projeto criado na GCP, ambos os dois comandos estão especificados 
com a ID do projeto criado e prontos para rodar via terminal, direto para o Google CLoud Run.

Também foi alterada a pate final do projeto app.py, parte do Run Service.


O servidor foi alterado do modo debug=True,  para: if __name__ == '__main__':
                                                      app.run_server(debug=False, host="0.0.0.0", port=8080)

Especificando a porta e host para o deploy                                                      
    


LINK Gerado para visualização do Dashboard ==> https://dashboard-3bnpxawmfa-rj.a.run.app/
  

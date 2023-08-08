# Projeto Movie
Projeto desenvolvido para aprendizado de Exploração de Dados com Python utilizando a biblioteca Pandas para analisar dados sobre avaliação de filmes a partir da base de dados do Kaggle

## Habilidades Desenvolvidas
A partir da base de dados extraída do <a href="https://grouplens.org/datasets/movielens/" target="_blank"> Movie Lens</a>, as informações foram agrupadas. Dessa forma, foi criado um objeto do tipo DataFrame no Pandas. Isso permitiu o cálculo da média de variáveis importantes para o estudo.
![image](https://github.com/KelsonHenrique/movie-project/assets/141082201/bc612476-5a57-4ae7-a3b9-5bc2a40f0842)

No entanto, não faz sentido calcular a média do Id de usuário, tampouco, o momento em que a pessoa foi entrevistada (variável "Momento"). Neste, caso usa-se o comando:
```
notas.groupby('filmeId').mean().nota
```
para colher apenas a média das notas de cada filme

Além disso, o comando foi definido dentro de uma variável chamada "medias_por_filme", descrita abaixo:
```
medias_por_filme = notas.groupby('filmeId').mean().nota
```
![image](https://github.com/KelsonHenrique/movie-project/assets/141082201/4b664872-8f8c-47ed-8aa9-28610196be15)


Gráfico elaborado usando a biblioteca do python usando uma base de dados de
![image](https://github.com/Kelsonhenrique7/movie-project/assets/141082201/c6242cd3-51b6-4fa9-abe5-a844ff084641)


## Como executar esse projeto 

- Instale Python versão 3.10.7;
- Instale o Anaconda para obter o jupyter notebook na sua máquina;
- Essa instalação permite que você obtenha muitas bibliotecas relevantes para executar seu projeto;
- Escolha, dentro do prompt de comando, o diretório onde irá realizar o seu projeto
- Após a escolha do diretório, execute o comando a seguir para iniciar os trabalhos:
```
jupyter notebook
```
- Uma página do seu navegador será aberta, exibindo todas as pastas do diretório escolhido no comando anterior;
- A partir daí, selecione "New > Python 3 (ipykernel)". Então, a interface do jupyter abrirá para você iniciar a syntax.
 
  



# pandas-entradas-e-saidas

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/pandas-entradas-e-saidas)
![Badge de Atualização](https://img.shields.io/github/last-commit/fab-souza/pandas-entradas-e-saidas)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Pandas: entradas e saídas**
| :label: Tecnologias | python
| :rocket: URL         | https://github.com/fab-souza/pandas-entradas-e-saidas/
| :fire: Desafio     | Conteúdo do curso [Pandas: formatos diferentes de entrada e saída (IO)](https://cursos.alura.com.br/course/pandas-io)

![](https://user-images.githubusercontent.com/67301805/208135938-c83ff4a2-951e-4dff-958a-bb3199690357.jpg#vitrinedev)

## Sobre o curso 📚

O curso simula o desenvolvimento do banco de dados de uma escola de programação, iniciando com arquivos no formato json, compostos por nomes de alunos, sua região, sua frequência, sua posição no rank e gênero, que serviu como fonte para os nomes. Em seguida, foi atribuído, de forma randômica, um id, email e número de cursos para cada aluno. Ao final, aprendi como fazer a exportação do dataframe no formato SQL e Excel, consequentemente, de como fazer a leitura destes arquivos.


## Minha prática 👩🏻‍💻

Pensei em fazer algo semelhante, ao usar o dataset [US Baby Name Popularity](https://www.kaggle.com/datasets/robikscube/us-baby-name-popularity?select=names.csv), disponível no [Kaggle](https://www.kaggle.com/), e para a parte dos cursos, usei o [College Majors and their Graduates](https://www.kaggle.com/datasets/thedevastator/uncovering-insights-to-college-majors-and-their), também do Kaggle.


O dataset de nomes contém uma quantidade maior do que 2 milhões de nomes, por isso limitei os registros até o ano de 2020 e foi reduzido a quase 32.000 registros. Desta seleção, há quase 29 mil registros únicos. Usei o *.random*, do Numpy, para atribuir um número para cada registro do dataframe, para se tornar o index, enquanto o id original se torna o número de registro do aluno. Ao invés de adicionar um email para cada aluno, crie uma nova variável que mostra a situação dos alunos, se eles ainda estão estudando, se já concluíram ou se o curso foi interrompido. 

A partir do dataset sobre as graduações nos EUA, usei os 173 cursos para distribuir entre os alunos do dataframe que desenvolvi e fiz a exportação para o formato csv, json e html. 

![out csv](https://user-images.githubusercontent.com/67301805/208662177-e74872db-25f3-437a-a437-a19246ec1317.jpg)

Para acessar o notebook que fiz no Kaggle, [clique aqui](https://www.kaggle.com/code/fabianadesouza/pandas-entradas-e-saidas).

Muito obrigada por chegar até aqui e até a próxima 🤗 


---
<h3>Ferramentas utilizadas:</h3>
    <p> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
        <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> 
        <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" alt="numpy" width="40" height="40"/>
          </p>

Boas práticas ao realizar projetos:

1 - Clean Code
2 - Utilizar uma PEP como padrão de desenvolvimento de código
3 - Requirements.txt
4 - Docker
5 - README
6 - Fazer pytest / pip install pytest
7 - Verificar arquivos  usando pylint (LINTER)
8 - Sempre criar uma nova branch e ou  subir o projeto para a essa branch develop
9 - Só deve subir o projeto para main quando tiver 100% de certeza que o projeto não tem bugs


Criando branch develop e subindo pro git:

1 - git branch

2 - git branch develop main ou git checkout -b develop

3 - git branch

4 - git checkout develop

5 - git branch

6 - git status

7 - git add novoExemplo.py ou git add .

8 - git commit -m "Adicionando readme e novoExemplo"

9 - git push --set-upstream origin develop

Observação, caso atualize um projeto faça o seguinte comando antes do git push:

1 - git pull

Fazendo merge entre a branch develop e a branch master

Antes de começar também execute os seguintes comandos no terminal do seu diretório:

1 - pip install pylint
2 - pip install pycodestyle


Ainda no diretório do projeto vamos Verificar com cada bilioteca o que elas vão nos apontar em cada arquivo:

1 - python -m pylint main.py
2 - python -m pycodestyle main.py
3 - python -m pylint fizzbuzz.py
4 - python -m pycodestyle fizzbuzz.py   
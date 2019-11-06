Start project Python Django

1 Criar pasta do projeto

2 Instalar virtualenv com a versão do Python

3 Iniciar ambiente virtual `virtualenv venv`

4 Na pasta `bin` executar `source activate`

5 Para voltar ao global `deactivate`

## Django

Com o ambiente virtual rodando

Instale o django `pip install django`

Rode `python`

Importe `import django`

Verifica a versão `django.get_version()`

Ou apenas execute `python -m django --version`

Cria um projeto `django admin.py startproject name_of_project`

Onde tiver o arquivo manage.py executar `python manage.py runserver`

Sync banco de dados `python manage.py migrate` ou `python manage.py migrate --run-syncdb`

Criar uma nova aplicação `python manage.py startapp core`

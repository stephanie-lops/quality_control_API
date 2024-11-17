------ ENGLISH -------

# My API - Stephanie Lopes

This project is the draft version of my MVP from Sprint 1 of the **Basic Full Stack Development** course.

The goal here is to list the products from an industry that have undergone Quality Control review.

Using 3 pieces of information: Serial Number, Defect, Status.

---
## How to run

You will need to have all the Python libs listed in `requirements.txt` installed.

After cloning the repository, you need to go to the root directory, via the terminal, to be able to run the commands described below.

> It is strongly recommended to use virtual environments such as [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).

Create virtual environment env

```
python3 -m venv env
```

Activate virtual environment env (Windows)

```
.\env\Scripts\activate
```

```
(env)$ pip install -r requirements.txt
```

This command installs the dependencies/libraries described in the `requirements.txt` file.

To run the API, simply run:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

In development mode, it is recommended to run using the reload parameter, which will restart the server
automatically after a change in the source code.

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Open [http://localhost:5000/#/](http://localhost:5000/#/) in your browser to check the status of the running API.

------ PORTUGUESE -------

# Minha API - Stephanie Lopes

Este projeto é a versão esboço do meu MVP da Sprint 1 do curso de **Desenvolvimento Full Stack Básico**.

O objetivo aqui é listar os produtos de uma industria que passaram por revisão do Controle de Qualidade.

Utilizando 3 informações: Número de Série, Defeito, Status.

---
## Como executar 


Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).

Criar ambiente virtual env

```
python3 -m venv env
```

Ativar ambiente virtual env (Windows)

```
.\env\Scripts\activate
```

```
(env)$ pip install -r requirements.txt
```

Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.

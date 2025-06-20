# Triagem Médica - SEGUNDO SEMESTRE (2022)

Este é um projeto de sistema de triagem médica, onde médicos podem cadastrar pacientes, registrar atendimentos e visualizar as urgências dos pacientes.

## Requisitos de Instalação

Antes de executar o projeto, certifique-se de ter as seguintes dependências instaladas:

- Python (versão 3.x): [Download Python](https://www.python.org/downloads/)
- Flask: Instale usando `pip install Flask`
- Flask SQLAlchemy: Instale usando `pip install Flask-SQLAlchemy`
- Flask Login: Instale usando `pip install Flask-Login`
- Werkzeug: Instale usando `pip install Werkzeug`

## CADASTRO DE USUÁRIOS
![image](https://github.com/user-attachments/assets/d65e88d1-757b-4084-84b9-141bef814ca1)

## LOGIN
![image](https://github.com/user-attachments/assets/f8bea130-ae2d-444d-b96f-7e8260f045fc)

## CADASTRO DE PACIENTES
![image](https://github.com/user-attachments/assets/7c622239-534e-42d0-9109-a63007915185)

## ATENDIMENTO
Na hora da realização do atendimento, é feito um cáculo de "urgência" de acordo com as informações do atendimento. Para esse cálculo, utilizei a variável "urgencia" para que seja somado a ela o nível de pressa que o paciente teria que ser atendido.
![image](https://github.com/user-attachments/assets/e9f290e8-0c6f-441c-8ee7-4a4228645add)

## Quadro de urgência
Nesse quadro, aparecem primeiro os pacientes com maior urgência, ou seja, o paciente que tinha problemas mais graves, portanto o valor da variável era maior.
![image](https://github.com/user-attachments/assets/706c1838-1138-415b-a03f-fe8ae87b79c1)

## ATENDER PACIENTE
Ao clicar no paciente no quadro de urgência, você pode "atender" ele e visualizar suas informações. Sendo atendido, ele não irá mais aparecer no quadro de urgências.
![image](https://github.com/user-attachments/assets/cdddedab-701e-48aa-9d07-cd308ffd033c)





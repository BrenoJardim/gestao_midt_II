# Sistema de Gestão ERP

## Descrição

Este projeto é um Sistema de Gestão ERP (Enterprise Resource Planning) desenvolvido em Flask, com o objetivo de ajudar empresas a gerenciar suas operações diárias de forma eficiente. O sistema inclui funcionalidades para gerenciar vendas, compras, produtos e muito mais.

## Funcionalidades

- Cadastro e gerenciamento de produtos
- Registro de vendas e compras
- Relatórios de vendas
- Previsão do clima utilizando a API WeatherAPI
- Interface amigável e responsiva

## Tecnologias Utilizadas

- **Backend**: Python com Flask
- **Banco de Dados**: [SQLite](https://www.sqlite.org/)
- **Frontend**: HTML, CSS, JavaScript
- **API**: [WeatherAPI](https://www.weatherapi.com/)
- **Testes**: Unittest, Selenium

## Requisitos

Para rodar este projeto, você precisará do Python e das seguintes bibliotecas:

- Flask
- requests
- blinker
- click
- itsdangerous
- Jinja2
- MarkupSafe
- Werkzeug

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO
   
2. Crie um ambiente virtual (opcional, mas recomendado):

  python -m venv venv
  source venv/bin/activate  # Para Linux/Mac
  venv\Scripts\activate  # Para Windows

3. Instale as dependências:

  pip install -r requirements.txt

4. Execute a aplicação:
   
  python app.py

5. Acesse a aplicação em http://127.0.0.1:5000.



Testes
Os testes para a aplicação podem ser executados com os seguintes comandos:

Testes Unitários
  python -m unittest discover

Testes Selenium
Certifique-se de que o ChromeDriver está instalado e configurado corretamente. Para rodar os testes Selenium:
  python test_selenium.py

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

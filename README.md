### Curso Técnico de Desenvolvimento de Sistemas - Senai Itapeva
## Status
Projeto concluído!

# EmpreGO

![imagem de capa](static/img/EMPRE%20(1).png)

## Descrição:
O projeto possui o objetivo de conectar empresas e candidatos permitindo a divulgação de vagas e a busca de oportunidades de emprego. A aplicação conta com funcionalidades específicas para usuários administradores, empresas e visitantes. Ele é composto por um sistema de autenticação, uma interface para administradores e empresas, além de funcionalidades para visualização e candidatura a vagas.


# índice 
* [Status](#status)
* [Funcionalidades](#funcionalidades)
* [Tecnologias](#tecnologias-utilizadas)
* [Autores](#autores)
* [Pré-Requisitos](#pré-requisitos)
* [Instalação e Configuração](#instalação-e-configuração)
* [Licença](#licença)

## Funcionalidades
**Autenticação de Usuário:**
- Login para administradores e empresas.
  
  **Login(ADM):**
  ![gif](static/img/gif/login_adm.gif)

  **Login(Empresas):**
  ![gif](static/img/gif/login_empre.gif)

- Sessões seguras utilizando Flask-Session.
- Busca de Vagas: Permite buscar vagas por palavras-chave no título ou descrição.

    **Buscar Vagas:**
    ![gif](static/img/gif/buscar_vaga.gif)

- Candidatura a Vagas: Usuários podem se candidatar ás vagas enviando o seu currículo (PDF).

    **Candidatura:**
    ![gif](static/img/gif/candidatura.gif)

**Gerenciamento de Empresas (Admin):**
- Cadastro, edição, ativação/desativação e exclusão de empresas.

    **Cadastro:**
    ![gif](static/img/gif/cadastro_empre.gif)

    **Edição:**
    ![gif](static/img/gif/editar_empre.gif)

    **Ativação/Desativação:**
    ![gif](static/img/gif/ativar-inativar_empre.gif)

    **Exclusão:**
    ![gif](static/img/gif/excluir.png)

**Gerenciamento de Vagas (Empresa):**
- Cadastro, edição, ativação/desativação e exclusão de vagas.

    **Cadastro:**
    ![gif](static/img/gif/cadastrar_vaga.gif)
    
    **Edição:**
    ![gif](static/img/gif/editar_vaga.gif)

    **Ativação/Desativação:**
    ![gif](static/img/gif/ativar-inativar_vaga.gif)

    **Exclusão:**
    ![gif](static/img/gif/excluir_vaga.gif)

**Candidaturas:**
- Envio de currículos em formato PDF para vagas ativas.
![gif](static/img/gif/envio_curri.gif)

**Visualização Pública:**
- Página inicial com listagem de vagas ativas e detalhes das vagas.
![gif](static/img/gif/pagina_inicial.gif)

## Tecnologias Utilizadas
**Linguagem/Frameworks:**
- ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
- ![css](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![html](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
- ![javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
- ![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)
- ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

## Pré-requisitos
**Certifique-se de ter as seguintes ferramentas instaladas antes de executar o projeto:**

- Python 3.x
- Pip (gerenciador de pacotes do Python)

## Instalação e Configuração
**1 - Instalar Python 3.x**
- Acesse o site oficial do Python: https://www.python.org/downloads/.
- Faça o download da versão mais recente do Python 3.x para o seu sistema operacional (Windows, macOS ou Linux).
- Durante a instalação, marque a opção "Add Python to PATH" para facilitar o uso do Python no terminal.

**2 - Instalar o Pip (Gerenciador de Pacotes do Python)**
- O Pip geralmente é instalado automaticamente com o Python. Para confirmar, execute o seguinte comando no terminal:
 --bash-- **pip --version**  
- Se o Pip não estiver instalado, siga as instruções na documentação oficial do Pip.

**3 - Instalar o Git**
- Faça o download e instale o Git: https://git-scm.com/.
- Após a instalação, verifique se está funcionando com o comando:
 bash **git --version**

**4 - Instalar as Dependências Necessárias Individualmente**
- Execute os seguintes comandos no terminal para instalar cada biblioteca necessária:

- Flask (Framework Web):
bash **pip install flask** 

- E após o comando acima insira a seguir o seguinte comando para estabelecer conexão com o banco de dados: bash **pip install mysql-connector-python**

**5 - Executar o Projeto**
- Certifique-se de estar na pasta do projeto.
- Inicie o servidor Flask no terminal:
  bash
  **python app.py**  
- Abra um navegador e acesse:
  http://127.0.0.1:5000

## Autores
- Yasmim Bueno de Morais - GitHub - https://github.com/YMorais/

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
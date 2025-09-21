-----

# KL\_PERFUME
### Sobre o Projeto

O **KL\_PERFUME** é um sistema web simples e eficiente para o controle e gerenciamento de vendas de cosméticos. Desenvolvido para facilitar a gestão do negócio, o sistema permite que o usuário gerencie produtos, clientes e vendas de forma organizada, além de fornecer uma visão analítica do desempenho através de painéis e gráficos interativos.

## Funcionalidades Principais

  - **Sistema de Contas:** Cadastro e login de usuários com gerenciamento de sessões, garantindo acesso seguro à plataforma.
  - **Gerenciamento Completo:**
      - **Produtos:** Controle de estoque, cadastro, edição e visualização de produtos.
      - **Clientes:** Cadastro de clientes para rastreamento de vendas.
      - **Vendas:** Registro e acompanhamento de transações de venda.
  - **Visualização Detalhada:** Páginas de detalhes para cada produto, cliente e venda, exibindo informações completas.
  - **Dashboard Gerencial:**
      - **Gráficos:** Visualização interativa com dados essenciais, como:
          - Quantidade de vendas por produto.
          - Vendas realizadas por cliente.
          - Faturamento total por mês.
      - **Indicadores Financeiros:** Exibição de saldo atual e valores a receber para uma gestão financeira rápida.

## Tecnologias Utilizadas

  - **Backend:**
      - **Python**
      - **Django** Framework
  - **Frontend:**
      - **HTML5**
      - **CSS3**
      - **Bootstrap** (para o design responsivo)
      - **JavaScript**
      - **Anychart** (para a criação de gráficos interativos)
  - **Banco de Dados:**
      - SQLite3
-----
## Estrutura de URL's
- `http://127.0.0.1:8000/admin/`
- `http://127.0.0.1:8000/auth/`
  - `http://127.0.0.1:8000/auth/cadastro/`
  - `http://127.0.0.1:8000/auth/login/`
  - `http://127.0.0.1:8000/auth/sair/`
- `http://127.0.0.1:8000/home/`
- `http://127.0.0.1:8000/caixa/`
-----
## Como Rodar o Projeto

### Pré-requisitos

Certifique-se de ter o Python 3 instalado em sua máquina.

### Instalação

1.  Clone o repositório:

    ```bash
    git clone https://github.com/Matheo-Henrique-Moura-Silva/kl-perfume-v01.git
    ```

2.  Navegue até o diretório do projeto:

    ```bash
    cd kl-perfume-v01-main
    ```

3.  Crie e ative um ambiente virtual:

    ```bash
    python -m venv venv
    source venv/bin/activate  # Para Linux/macOS
    venv\Scripts\activate      # Para Windows
    ```

4.  Instale as dependências listadas no `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

5.  Execute as migrações do banco de dados:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6.  Crie um superusuário para acessar o painel administrativo:

    ```bash
    python manage.py createsuperuser
    ```

7.  Inicie o servidor de desenvolvimento:

    ```bash
    python manage.py runserver
    ```

Acesse o sistema no seu navegador em: `http://127.0.0.1:8000/`.

-----
# IMAGENS
![Tela de LOGIN do sistema](screenshots/a(7).png)
![Tela de CADASTRO do sistema](screenshots/a(8).png)
![Tela DASHBOARD do sistema](screenshots/a(5).png)
![Tela de PRODUTOS do sistema](screenshots/a(9).png)
![Tela de CLIENTES do sistema](screenshots/a(10).png)
![Tela de CLIENTE do sistema](screenshots/a(1).png)
![Tela de DIVIDA POR CLIENTE do sistema](screenshots/a(2).png)
![Tela de VENDAS do sistema](screenshots/a(6).png)
![Tela de VENDAS POR CLIENTES do sistema](screenshots/a(4).png)
![Tela de VENDAS POR PRODUTOS do sistema](screenshots/a(3).png)
-----

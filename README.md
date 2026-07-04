# Demo Django + Tailwind CSS 🐳

Este é um projeto de demonstração simples desenvolvido em **Django 5.1.3**[cite: 1] e estilizado com **Tailwind CSS** via CDN, totalmente conteinerizado utilizando o **Docker**.

## 🚀 Tecnologias Utilizadas

- **Python 3.12-slim** (Imagem base do contêiner)[cite: 1]
- **Django 5.1.3** (Framework web backend)[cite: 1]
- **Tailwind CSS** (Framework de estilização de interfaces)
- **Docker & Docker Compose** (Orquestração do ambiente de desenvolvimento)[cite: 1]
- **SQLite** (Banco de dados local)

## 🛠️ Como Executar o Projeto Localmente

Para iniciar o ambiente de desenvolvimento, certifique-se de ter o Docker instalado e siga estes passos:

1. Clone este repositório ou navegue até a pasta raiz do projeto.
2. Execute o seguinte comando para construir a imagem, aplicar as migrações do banco de dados automaticamente e iniciar o servidor:

```bash
docker-compose up
```

3. Abra o seu navegador e acesse o seguinte endereço:
   👉 **[http://localhost:8000](http://localhost:8000)**

### 👤 Painel de Administração do Django

Para gerenciar os dados e acessar o painel administrativo:
1. Acesse `http://localhost:8000/admin/`
2. Se precisar criar um usuário administrador, abra um novo terminal e execute:
   ```bash
   docker-compose run --rm web python manage.py createsuperuser
   ```

## 📂 Estrutura Principal do Projeto

- `core/`: Contém as configurações principais do Django (`settings.py`, `urls.py`, etc.)[cite: 1].
- `home/`: Aplicativo responsável por gerenciar a lógica inicial e as páginas do sistema[cite: 1].
- `templates/home/`: Arquivos HTML do frontend com componentes dinâmicos do Django e Tailwind CSS[cite: 1].



<img width="1600" height="774" alt="123123" src="https://github.com/user-attachments/assets/89d4510d-0160-45c4-91a7-8b92974d70ba" />



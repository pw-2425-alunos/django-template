# django-template

Este repositório serve como um template base para projetos **Django** que usem o **Neon** como base de dados psql e o **Cloudinary** para storage de ficheiros do media, permitindo iniciar rapidamente um novo projeto com uma estrutura pré-configurada.

## Propósito

O `django-template` foi criado para ser um ponto de partida para projetos Django. Pode clonar este repositório e importar o seu projeto Django existente, aproveitando a configuração inicial já preparada.

## Conteúdo

- **.github/workflows**: Contém os ficheiros de configuração para o pipeline CI/CD, que automatiza o build, push e deploy da imagem Docker.
- **.gitignore**: Define os ficheiros e pastas a serem ignorados pelo Git, como ficheiros temporários e ambientes virtuais.
- **Dockerfile**: Ficheiro de configuração para construir a imagem Docker da aplicação Django. Atenção que `project` deve corresponder ao nome da pasta onde está `settings.py`.
- **docker-compose.yml**: Configuração para orquestrar serviços com Docker Compose, útil para desenvolvimento local.
- **requirements.txt**: Lista as dependências Python necessárias para o projeto.

## Configuração

Siga os passos da [Ficha 10](https://programacao-web.gitbook.io/ficha-8-26-ci-cd) para configurar o seu projeto

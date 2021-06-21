# DrupalSite

*Estamos usando Drupal 7.81.*

**Entregas:**

 1. v1.0: Instalação padrão do Drupal 7 funcionando.
 2. v1.1: Criar um Content Type de eventos e registrar alguns eventos no CMS. Conter foto, endereço, dias e horários, staff e palestrantes, outras informações que achar interessante. Considerar que nem todos os eventos possuem todas as informações. Ex.: eventos online não possuem endereço.
 3. v1.2: Adicionar um tema da comunidade e ativar ele para mudar a aparência do site.
 4. v1.3: Criação de um módulo custom, seguir a estrutura de módulos indicada pelo site da comunidade do Drupal. Esse módulo deve criar um Block (usando hooks) que vai adicionar um conteúdo simples nas páginas de eventos (texto e/ou imagem).

# Comentários sobre o meu trabalho:

 - v1.1 -> Criei o Content Type "Eventos";
 - v1.2 -> Adicionei um tema chamado "Mayo";
 - v1.3 -> Criei um módulo que adiciona um block no banner top da página com os links para os nodes dos eventos criados e ativos nos últimos 7 dias.

# Preparando o ambiente de desenvolvimento
Os items da lista abaixo é uma forma de preparar o ambiente local usando "Docker":

### Docker
1.  [Instale o Docker](https://docs.docker.com/install/#supported-platforms) no seu ambiente;
2. Inicialize o container com o comand line: ``$ docker-compose up -d``;
3. Entre em http://localhost:8001/ para acessar o phpMyAdmin. E faça uma importação de uns dos backups da pasta "db-backups";
4. Por fim acesse http://localhost/.

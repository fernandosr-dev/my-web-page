# Desafios do Exercício

## 1. Configuração do GitHub Actions
- **Desafio**: Integrar GitHub Actions com DockerHub para CI/CD automatizado
- **Solução**: Configurar secrets no GitHub para credenciais do DockerHub e criar workflow para build e push automático

## 2. Dockerfile para Nginx
- **Desafio**: Copiar corretamente o arquivo index.html para o diretório do Nginx
- **Solução**: Usar a sintaxe correta `COPY index.html /usr/share/nginx/html/` no Dockerfile

## 3. Terraform para AWS ECS
- **Desafio**: Configurar provider AWS e criar cluster ECS com Terraform
- **Solução**: Definir corretamente o provider AWS com região e criar recurso aws_ecs_cluster no main.tf

## 4. Separação de Repositórios
- **Desafio**: Gerenciar dois repositórios distintos (aplicação e infraestrutura)
- **Solução**: Manter separação clara entre código da aplicação (my-web-page) e IaC (my-web-page-infra)

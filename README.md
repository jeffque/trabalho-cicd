# Trabalho CI/CD

Trabalho para a disciplina de CI/CD.

Integrantes:

- Janderson Siqueira
- Jefferson Quesado
- Otoni Cardoso

## Objetivo

Demonstrar aquisição de conhecimento sobre CI/CD explicados durante a disciplina.

- Uma aplicação
    - Source próprio
    - Com sistema de build (eg, `npm`, `maven` etc)
    - Um outro sistema além da própria aplicação (eg, banco de dados) descrito via `docker-compose.yaml`
- Rodar testes automaticamente
- Subir um ambiente de build com Jenkins e Sonar Qube
- Empacotar a versão em uma imagem Docker
- Atualizar um ambiente de produção com Kubernetes

## Rodando a aplicação

Para rodar a aplicação em modo de desenvolvimento:

```bash
npm dev
```

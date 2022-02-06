# k6_k8s_tests

Este repositório contém o material do curso [Testes de Performance em Aplicações Modernas](http://url_do_curso).

## Dependências
Abaixo encontrará as referências à outros projetos e dependências que utilizamos no curso. 

* [Docker Desktop](https://www.docker.com/products/docker-desktop) - Vamos correr o ambiente todo em docker e kubernetes. Por isso será essencial ter o docker desktop instalado e rodando.

* [MicroServices Demo - GCP](https://github.com/GoogleCloudPlatform/microservices-demo) - Aplicação utilizada como alvo dos testes.
 Para essa aplicação rodar localmente, utilize o guia no repositório original: [Guia de deploy local](https://github.com/GoogleCloudPlatform/microservices-demo/blob/main/docs/development-guide.md#option-2---local-cluster). 
  O conteúdo necessário para sua execução está incluso como uma dependência no arquivo `.gitmodules` adicionado na raiz deste projeto.

* [k6](https://k6.io/docs/getting-started/installation/#docker) - O k6 é a ferramenta de load tests que vamos utilizar, e de preferência deve ser instalado via docker. 




Este guia tem como finalidade te auxilar a criar a imagem Docker, subir o container e usar os recursos da norminette em seu pc.

1. Certifique-se de ter o Docker instalado:
    - https://www.nerdlivre.com.br/como-instalar-o-docker-no-ubuntu/

2. Crie a imagem Docker:
    - Opção 1: Crie a imagem em um único comando:
        - sudo docker build -f debian_docker_dev -t debian_dev .
    
    - Opção 2: Renomeie o arquivo antes de criar a imagem:
        - cp debian_docker_dev Dockerfile
        - sudo docker build -t debian_dev .

4. Rode o container à partir da imagem criada:
    - docker run -it debian_dev:latest

5. Usando a Norminette:
    - Crie 1 ou N arquivos .c
    - Para validar todos os arquivos .c
        - norminette
    - Para validar um arquivo em específico
        - norminette arquivo.c

#### Comandos docker

- Iniciar todos os containers:
    - levando em consideração que os arquivos docker(docker-compoese.yml e Dockerfile) estão configurados, execute:
        - ```cmd 
                $ docker compose up
          ```

- Acessar o container
    - ```cmd 
            $ docker container exec -it <nome-container> <comando>. 
            Ex.: 
            $ docker container exec -it 759d1c3b9765 bash
      ```
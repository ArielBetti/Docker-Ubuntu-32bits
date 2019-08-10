ubuntu
======

Build do docker image para ubuntu i386.
   
    <h2>1º Clone o repositorio:</h2>
    git clone https://github.com/ArielBetti/Docker-Ubuntu-32bits
    <br>
    <h2>2º Rode o script de instalação:</h2>
    Entre na diretorio do repositorio:
    cd Docker-Ubuntu-32bits
    Execute o script:
    sudo bash build-image.sh
    <br>
    <h2>3º Verifique se tudo deu certo:</h2>
    <ul>
    <li>docker -v</li>
    <li>sudo docker run hello-world</li>
    </ul>

Veja também:
 - https://github.com/ioft/dockerhub
 - http://mwhiteley.com/linux-containers/2013/08/31/docker-on-i386.html
 - https://dzone.com/articles/docker-daemon-for-32-bit-architecture

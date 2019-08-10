<h1>Docker no Linux Ubuntu i386</h1>

Build do docker image para ubuntu i386.
   <h2>1º Clone o repositorio:</h2>

  `git clone https://github.com/ArielBetti/Docker-Ubuntu-32bits`

   <h2>2º Rode o script de instalação:</h2>
	
Entre no diretorio:`cd Docker-Ubuntu-32bits`

  Execute o script:`sudo bash build-image.sh`
  
<h2>3º Verifique se tudo deu certo:</h2>

  `docker -v`
  
  `sudo docker run hello-world`
  
  <h2>Veja também</h2>
  
Repositorio original:

 - https://gitlab.com/docker-32bit/ubuntu
  
Outros:
 - https://github.com/ioft/dockerhub
 - http://mwhiteley.com/linux-containers/2013/08/31/docker-on-i386.html
 - https://dzone.com/articles/docker-daemon-for-32-bit-architecture

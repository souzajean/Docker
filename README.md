# Docker

<h1>Instalando o Docker</h1><br>
curl -fsSl https://get.docker.com | bash
<br>
<h1>sudo usermod -aG docker jean</h1><br>
<h1>Docker Versão</h1><br>
docker version
<br>
<h1>Docker Informação</h1><br>
docker info
<br>
<h1>Docker Container em execução</h1><br>
docker ps
<h1>Docker Container em execução versão novas</h1><br>
docker container ls
<br>
<h1>Executando o Container</h1><br>
docker container run -ti hello-world
<br>
<h1>Trazer todos os Container</h1><br>
docker container ls -a
<br>
<h1>Conectar direto no bash no container</h1><br>
docker container run -ti ubuntu
<p>Mostra processo em execução</p><br>
ps -ef
<br><p>Mostra versão do S.O</p><br>
cat /etc/issue
<br>
<h1>Conectar direto no bash no container</h1><br>
docker container run -ti centos
<br><p>Mostra processo em execução</p><br>
cat /etc/redhat-release
<br>
<p>Mostra processo em execução</p><br>
ps -ef
<br>
<h1>Sair do container sem matar a sessão</h1><br>
Ctrl+p+q
<br>
docker container ls
<br>
<h1>Conectando no container attach</h1><br>
docker container attach "CONTAINER ID" OU "Names"
<br>
<h1>Executando o Container</h1><br>
docker container run -ti nginx
<br>
<h1>Executando o Container como Daemon</h1><br>
docker container run -d nginx
<br>
<p>Verificando o container em execução</p><br>
docker container ls
<br>
docker container attach "CONTAINER ID" OU "Names"
<br>
<p>exit ---> CRTL+D</p>
<br><p>Verificando o container em execução - matou o container</p><br>
docker container ls
<h1>Como conectar no container em execução</h1><br>
docker container exec -ti "CONTAINER ID" OU "Names" ls /
<br>
docker container exec -ti "CONTAINER ID" OU "Names" bash
<br>
docker container exec -ti 049a785ef131 cat /usr/share/nginx/html/index.html
<br>
<h1>Docker Images baixadas</h1><br>
docker images
<br>

<br>


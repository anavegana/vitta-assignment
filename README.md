# vitta-assignment

##Descrição do projeto
Um serviço que integra o XXX como plataforma de YYY.

##A quem se destina/objetivo
Este projeto é mantido sob o mais absoluto sigilo para a Empresa ZZZ. Se você está vendo isso certamente você faz parte do projeto. O objetivo deste documento é facilitar a compreenção do escopo do projeto e de como funciona.


###Instalação  local
• Instale apache, php e sql ao seu modo (xampp, wamp ou individual), instale o composer e o git; • Em seu servidor local baixe o projeto usando git clone; • Digite: composer install para instalar as bibliotecas; • Instale database.sql em PHPMyAdmin; • Agora, para que o envio de e-mail funcione localmente habilide a extensão open_openssl e php_sockets* no php.ini, basta abrir o php.ini e usando Ctrl+F busque pelos termos openssl, descomente e depois depois repita os procedimentos para sockets, não se esqueça de reiniciar o apache depois do procedimento;

###Desenvolvimento
Essa seção explica o que é necessário fazer para evoluir o projeto, ou seja, desenvolver novas funcionalidades no mesmo. No nosso caso, é necessário apenas clonar o projeto do GitHub num diretório de preferência do usuário.

####Construção
Aqui você vai informar os comandos necessários para construir o seu projeto. Como se trata de um projeto Maven, vamos adicionar apenas o comando básico de construção mvn clean install.
ex(O comando irá baixar todas as dependências do projeto e criar um diretório target com os artefatos construídos, que incluem o arquivo jar do projeto. Além disso, serão executados os testes unitários, e se algum falhar, o Maven exibirá essa informação no console.)

#####Features
Aqui você vai dizer o que o seu projeto faz, o que ele poderia vir a fazer, basicamente tudo que ele oferece para o usuário. Para o nosso projeto, sabemos que ele pode servir como um projeto Maven inicial para outros desenvolvedores, além de demonstrar como configurar o Maven em um projeto Java.

######Teste
Para rodar o teste,utilizar:
<input name="debugMode" type="hidden" value="true" />

#######Licença
Projetos de Open Source precisam ser licenciados corretamente para que os usuários saibam o que podem fazer com ele. A licença correta evita muitos problemas de autoria e por isso deve ser bem pensada para o projeto. Recomendo esse site, que orienta de forma prática a escolha da licença adequada para o seu projeto. No caso do nosso projeto, não adicionarei licença.

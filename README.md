# Felipe Silva

## Introdução

Estou na área de Desenvolvimento de Software desde 2017 quando fiz Ensino Médio Técnico em Informática na Escola ETEP até 2019. De 2020 até o presente estou cursando Análise e Desenvolvimento de Sistemas na Fatec. De 2020 até Setembro de 2021 estagiei na empresa de soluções integradas GSW onde tive a oportunidade de palestrar sobre chatbot na Fatec, após esse periodo, fui aprovado no estágio de TI da Embraer onde trabalho até hoje.
![image](https://user-images.githubusercontent.com/65372142/159736953-152cb85c-3519-4bbe-8edd-f88067084215.png)


## Meus Projetos

### Em 2020-1
O projeto TempVerify teve como empresa parceira a propria FATEC que propos a criação de um sistema de regulamento de temperatura e umidade do ar para proporcionar mais conforto ao cliente. Aceitado o desafio, a equipe Hexagono desenvolveu o dispositivo TempVerify que permitia ler a temperatura e umidade do ambiente e regular os mesmos através de um dispositivo físico controlado por aplicativo.

[GIT](https://github.com/cacauisadog/hexagono-fatec) 


#### Tecnologias Utilizadas
-Firebase: Banco de dados não relacional com acesso em nuvem, utilizado para o armazenamento das informações de login dos usuários.

-Flutter: Framework de código aberto para a linguagem Dart

-NodeMCU: Plataforma hardware de IoT(internet of Thing, Internet das Coisas) que foi utilizada para a construção do dispositivo em si. Devido a proporção baixa do projeto e a praticidade para conexões de internet, julgamos ser o dial para o desenvolvimento.

-OneSignal: Ferramenta web que permite notificar dispositivos móveis. A pesar de algumas funcionalidades pagas, os recursos gratuitos permitiram enviar as notificações desejadas aos usuários.

#### Contribuições Pessoais
![image](https://user-images.githubusercontent.com/65372142/160295513-6258abab-1582-4c4b-9452-5c780b8ce8ca.png)

Devido minha familiaridade com Banco de Dados auxiliei meus colegas de equipe com essa frente. Primeiramente deve se inserir os dados de rede do usuarioSSID e senha) para que seja estabelecida a conexão, em seguida, o banco de dados também precisa ser conectado através de seu link e senha e por fim definir o tipo de ligação do DHT11 e o tipo de sensor DHT. Além do banco de dados também auxiliei com a documentação do projeto.

#### Hard Skills
Firebase - Sei fazer com ajuda

C++ - Sei fazer com ajuda

#### Soft Skills
Comunicação - Como ingressante na faculdade foi crucial desenvolver minha comunicação com os novos companheiros.

Adaptabilidade - Desconhecendo muitas das tecnologias necessarias para o projeto, me vi na obrigacao de me adaptar a elas para auxiliar a equipe.

### Em 2020-2
O projeto do segundo semestre teve como empresa parceira, alem da propria FATEC, a IACIT que propos um problema real que precisava ser solicionado, desenvolver um programa de controle e gerenciamento das jornadas de seus motoristas. O projeto deveria envolver a parametrização das informações, controle, acompanhamento e conter relatorios analíticos.

[GIT](https://github.com/Vitor-y/Projeto-Integrador) 


#### Tecnologias Utilizadas
-PostgreSQL 9.5: Banco de dados relacional, utilizado para o armazenamento das informações dos motoristas, seus veiculos e suas jornadas.

-Java 11: Linguagem orientada a objeto utlizada para a construção do Back-End do projeto

-NetBeans: IDE que suporta diversas linguagens diferentes, incluindo Java. Elegemos essa por considerela ideal para a execucao do projeto

#### Contribuições Pessoais

Assim como no primeiro semestre, me foquei na parte de Banco de Dados assim como suas conexões com o Back-End. Ressalta-se, inclusive, que devido a problemas de versionamento, foi necessaria a substituição de uma versão mais recente do PGAdmin(visualizador do PostgreSQL) por uma versão mais antiga para fins de ter a visão apropriada da base de dados.

Para que a conexçao seja feita, inicialmente, é necessario declarar as importações (como por exemplo a dependencia sql) e variaveis necessárias(como o usuário, a senha, o caminho do banco e o driver)
![image](https://user-images.githubusercontent.com/65372142/165761025-4e11ecdf-7c6b-4b09-bfcd-d65923d20062.png)

O método "conexao" é responsavel por conectar o projeto ao seu banco de dados, isso e feito atraves da funcao setProperty que utiliza as variaveis anteriormente declradas (caminho, usuario e senha) para conectar ao banco correto
![image](https://user-images.githubusercontent.com/65372142/165764292-89db85b9-1eb6-44ef-be15-dc0a6a13add4.png)

O método "executaSql" tem a funcao de enviar as queries necessarias para a utilizacao do projeto para o banco, como listar motoristas, realizar cadastros, deletar veiculos e atualizar dados
![image](https://user-images.githubusercontent.com/65372142/165766991-7718c74b-b8cd-42b3-b0f4-346d2e2e8ae7.png)

Por fim, o método "desconecta" e responsavel por desconectar o projeto do banco de dados
![image](https://user-images.githubusercontent.com/65372142/165767720-46fd6792-1a6e-472e-9090-9c8f6b110062.png)

Importante ressaltar que todos esses métodos estao dentro de um try catch, ou seja, caso haja algum erro na execussao de alguma delas, o erro sera reportado e a execussao cancelada.

Além da conexão com o banco de dados, também me responsabilizei por fazer os wireframes do porjeto, que são versões mock up de como a versão final do projeto ira se parecer, essas foram feitas n plataforma Figma. Nas imagens a abaixo é possivel ver o resultado final dos wireframes.

Login de usuario ou Admin:
![image](https://user-images.githubusercontent.com/65372142/165770392-46346885-f8b8-4e16-8be3-65f1a8fa8ece.png)

Login do Admin:
![image](https://user-images.githubusercontent.com/65372142/165770464-e55d9cbc-bd79-4523-8008-f97fb43c676f.png)

Login do Usuario:
![image](https://user-images.githubusercontent.com/65372142/165770547-fc8d4e41-7953-4831-8835-ce6c3ea9ab87.png)

Cadastro de Usuarios:
![image](https://user-images.githubusercontent.com/65372142/165770605-dc854867-70c9-4689-af2b-2cc5f46e0705.png)

Cadastro de Veiculos:
![image](https://user-images.githubusercontent.com/65372142/165770646-ab405505-1b20-48b7-9ed8-11dc5bc43e2a.png)

#### Hard Skills
Java - Sei fazer com autonomia

PostgreSQL - Sei fazer com autonomia

Figma - Sei fazer com ajuda

#### Soft Skills
Controle das emoções - Devido ao fato de, em determinado ponto do desenvolvimento, termos que refazer variass funcionalidades do aplicativo, foi necessario resiliencia para concertar ditoas funcionalidades a fim de entregar o projeto a tempo.

Gerenciamento do tempo - Mesmo estando envolvido em projetos no estágio, não podia deixar de auxiliar a equipe como fosse necessário.


### Em 2021-1
API-RGBA foi o 3º projeto de API em que eu participei. Teve como cliente a empresa Ness Health e como objetivo aperfeiçoar as capacidades técnicas de funcionários, tendo em vista o grabde aumento na procura de cursos on-line em decorrênciada pandemia e a notavel dificuldade de acesso a educação no Brasil. Para isso seriam disponibilizados, na plataforma, diversos treinamentos no qual o funcionário poderia ser designado a estudar.

[GIT](https://github.com/giovannialves01/API-RGBA) 


#### Tecnologias Utilizadas

Javascript - Linguagem utilizada em paginas web para codificar funcoes como mensagens de alerta que foram utilizadas para funcionalidades adicionais no front

Spring - Inicializador utilizado para criar projeto já com várias dependências que utilizariamos

CSS3 - Linguagem que permitiu criar os visuais que apareceriam na tela para o usuario

HTML5 - Linguagem utilizada para codificar as telas do Front-End

-PostgreSQL: Banco de dados relacional, utilizado para o armazenamento das informações dos cursos, alunos e professores.

-Java: Linguagem orientada a objeto utlizada para a construção do Back-End do projeto


#### Contribuições Pessoais
Nessa API eu participei de 4 funcionalidades principais.

1-Criacao da pagina de Log

No Front-End...

-Foi preciso adicionar o script do log em sua respectiva pagina para que seus métodos pudessem ser utilizados.

-Log significa registrar quaisquer acoes que afetaram o sistema com data e hora dessas acoes.
 
 -Para isso servira a div log, exibit as atividades e modificações feitas por usuários assim como quando eles fizeram isso.

![image](https://user-images.githubusercontent.com/65372142/166115026-b121f3a7-e4ea-487d-9cd6-604cb3734f09.png)


No Back-End...

-Um arquivo Java Script foi criado para armazenar os atributos de um log como resposta e entidades.

-Um laco for ira analisar todas as logs existentes e alimentar as variáveis com as informações encontradas através do text contente, que, a partir do texto           determinado, trará a informação a frente deles.
 
-A sessão de valor, por sua vez, trará o identificador de cada informação.

![image](https://user-images.githubusercontent.com/65372142/165949979-5dadc17d-22bf-40f8-be9c-96d95d8531d7.png)

  -O script adicionado no front possui os métodos de criação e importação dos conteúdos das logs com base no banco de dados, isso foi feito através de um constructor.
  -Caso o valor não seja encontrado, dados genéricos são enviados.
  -O constructor utilizara dos métodos get para obter as informações, enquanto as set serão utilizadas para a criação das logs.

2-

3-Atualização do Header
Para que essa funcionalidade do header fosse implementada, inicialmente, seria necessario criar seu estilo na página de css, ou seja, tecnologia utilizada para criação dos visuais na tela. Estilos esses que incluem, mas não se limitam a tamanho do header (width: 300px; height: 300px;), margem do texto do título (margin-left: 20px;) etc.

![image](https://user-images.githubusercontent.com/65372142/166114727-908be52e-c9cd-40be-8c38-68fd8c6a00b3.png)

Por fim, para verificar a funcionalidade do header, esse foi adicionado a página de notícias assim como um texto base.

![image](https://user-images.githubusercontent.com/65372142/166114796-d7d31999-9928-4ef1-a09e-54c54dd29f05.png)

4-Criação da página de notícias

Por fim, para a programação da página onde o usuário encontraria as notícias da plataforma, incialmente deveria se criar a celula head com informações como o titulo da página e conjunto de carateres a serem utilizados.

![image](https://user-images.githubusercontent.com/65372142/166113537-445cb863-ec1b-4376-b179-c849764d3c66.png)

O body a seguir, assim como suas divs, foi criado como placeholder para que o grupo pudesse ter noção de onde cada funcionalidade se encontraria na versão fiinal. Nele, é possivel ver a definição do estilo das imagens, como tamanho da borda (border: 1px solid gray), margem entre outros elementos da tela (margin: 10px) e tamanho dos elementos (height: 150px; width)

![image](https://user-images.githubusercontent.com/65372142/166114136-6a372596-8d9e-45c1-876b-3ee4c8a323b0.png)

O restante da página contém comentarios que mais tarde serviram para incorporar outras funcionalidades na página como lista de cursos, Bibliotecas, Questionários etc.

![image](https://user-images.githubusercontent.com/65372142/166114186-3dc7119f-bce6-445f-9d55-a681e6dce881.png)


#### Hard Skills 
Java - Sei fazer com autonomia

PostgreSQL - Sei fazer com autonomia


#### Soft Skills
Humildade - Em diversos momentos me deparei com situacoes onde eu deveria usar metodos que eu nao conhecia e me vi na necessidade de pedir ajuda aos demais colegar de equipe.

Comunicacao Interpessoal - Por me encontrar varias vezes necessitando de ajuda, era necessario comunicar propriamente minhas dificuldades e garantir que eu ja tinha feito tudo o que estava ao meu alcance para resolver antes de pedir auxilio.

### Em 2021-2
Mesmo formato

### Em 2022-1
Mesmo formato

## Meus Principais Conhecimentos
-Análise e Armazenamento de Dados

-Tecnologia de Chatbot

-Linguagem Java

## Contatos
* [GIT](https://github.com/Felipe-Silva2002 | https://github.com/Ffelipe-Ssilva)
* [LinkedIn](https://www.linkedin.com/in/felipe-silva-13b3b61a0)



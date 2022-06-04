# Felipe Silva

## Introdução

Estou na área de Desenvolvimento de Software desde 2017 quando fiz Ensino Médio Técnico em Informática na Escola ETEP até 2019. De 2020 até o presente, estou cursando Análise e Desenvolvimento de Sistemas na Fatec. De 2020 até setembro de 2021 estagiei na empresa de soluções integradas GSW onde tive a oportunidade de palestrar sobre chatbot na Fatec, após esse período, fui aprovado no estágio de TI da Embraer onde trabalho até hoje.
![image](https://user-images.githubusercontent.com/65372142/159736953-152cb85c-3519-4bbe-8edd-f88067084215.png)


## Meus Projetos

### Em 2020-1
O projeto TempVerify teve como empresa parceira a própria FATEC que propôs a criação de um sistema de regulamento de temperatura e umidade do ar para proporcionar mais conforto ao cliente. Aceitado o desafio, a equipe Hexágono desenvolveu o dispositivo TempVerify que permitia ler a temperatura e umidade do ambiente e regular os mesmos através de um dispositivo físico controlado por aplicativo.

[GIT](https://github.com/cacauisadog/hexagono-fatec) 

![image](https://user-images.githubusercontent.com/65372142/170793931-6b5f0daf-20ab-4338-9723-9eb0a28978e6.png)


#### Tecnologias Utilizadas
-Firebase: Banco de dados não relacional com acesso em nuvem, utilizado para o armazenamento das informações de login dos usuários.

-Flutter: Framework de código aberto para a linguagem Dart

-NodeMCU: Plataforma hardware de IoT(Internet of Things, Internet das Coisas) que foi utilizada para a construção do dispositivo em si. Devido a proporção baixa do projeto e a praticidade para conexões de internet, julgamos ser o ideal para o desenvolvimento.

-OneSignal: Ferramenta web que permite notificar dispositivos móveis. A pesar de algumas funcionalidades pagas, os recursos gratuitos permitiram enviar as notificações desejadas aos usuários.

#### Contribuições Pessoais

Devido minha familiaridade com Banco de Dados auxiliei meus colegas de equipe com essa frente. Primeiramente deve se inserir os dados de rede do usuarioSSID e senha) para que seja estabelecida a conexão, em seguida, o banco de dados também precisa ser conectado através de seu link e senha e por fim definir o tipo de ligação do DHT11 e o tipo de sensor DHT. Além do banco de dados também auxiliei com a documentação do projeto.

#### Hard Skills
Firebase - Sei fazer com ajuda

C++ - Sei fazer com ajuda

#### Soft Skills
Comunicação - Como ingressante na faculdade foi crucial desenvolver minha comunicação com os novos companheiros.

Adaptabilidade - Desconhecendo muitas das tecnologias necessárias para o projeto, me vi na obrigação de me adaptar a elas para auxiliar a equipe.

### Em 2020-2
O projeto do segundo semestre teve como empresa parceira, além da própria FATEC, a IACIT que propôs um problema real que precisava ser solucionado, desenvolver um programa de controle e gerenciamento das jornadas de seus motoristas. O projeto deveria envolver a parametrização das informações, controle, acompanhamento e conter relatórios analíticos.

[GIT](https://github.com/Vitor-y/Projeto-Integrador) 

![image](https://user-images.githubusercontent.com/65372142/170794024-b59ee095-e5bf-4a32-8af3-e31f09e06bcd.png)

#### Tecnologias Utilizadas
-PostgreSQL 9.5: Banco de dados relacional, utilizado para o armazenamento das informações dos motoristas, seus veículos e suas jornadas.

-Java 11: Linguagem orientada a objeto utilizada para a construção do Back-End do projeto

-NetBeans: IDE que suporta diversas linguagens diferentes, incluindo Java. Elegemos essa por considera-la ideal para a execução do projeto

#### Contribuições Pessoais

Assim como no primeiro semestre, participei parte de Banco de Dados assim como suas conexões com o Back-End. Ressalta-se, inclusive, que devido a problemas de versionamento, foi necessária a substituição de uma versão mais recente do PGAdmin(visualizador do PostgreSQL) por uma versão mais antiga para fins de ter a visão apropriada da base de dados.

Para que a conexão seja feita, inicialmente, é necessário declarar as importações (como por exemplo a dependência SQL) e variáveis necessárias(como o usuário, a senha, o caminho do banco e o driver)

O método "conexao" é responsável por conectar o projeto ao seu banco de dados, isso e feito através da função setProperty que utiliza as variáveis anteriormente declaradas (caminho, usuario e senha) para conectar ao banco correto.

O método "executaSql" tem a função de enviar as queries necessárias para a utilização do projeto para o banco, como listar motoristas, realizar cadastros, deletar veículos e atualizar dados.

Por fim, o método "desconecta" e responsavel por desconectar o projeto do banco de dados.

Importante ressaltar que todos esses métodos estão dentro de um try-catch, ou seja, caso haja algum erro em alguma delas, o erro sera reportado e a execução cancelada.

Além da conexão com o banco de dados, também participei da criação dos wireframes do projeto, que são versões mock-up de como a versão final do projeto ira se parecer, essas foram feitas na plataforma Figma.

![image](https://user-images.githubusercontent.com/65372142/165770392-46346885-f8b8-4e16-8be3-65f1a8fa8ece.png)

#### Hard Skills
Java - Sei fazer com autonomia.

PostgreSQL - Sei fazer com autonomia.

Figma - Sei fazer com ajuda.

#### Soft Skills
Controle das emoções - Devido ao fato de, em determinado ponto do desenvolvimento, termos que refazer variass funcionalidades do aplicativo, foi necessário resiliência para concertar essas funcionalidades a fim de entregar o projeto a tempo.

Gerenciamento do tempo - Mesmo estando envolvido em projetos no estágio, não podia deixar de auxiliar a equipe como fosse necessário.


### Em 2021-1
API-RGBA foi o 3º projeto de API em que eu participei. Teve como cliente a empresa Ness Health e como objetivo aperfeiçoar as capacidades técnicas de funcionários, tendo em vista o grande aumento na procura de cursos on-line em decorrência da pandemia e a notável dificuldade de acesso à educação no Brasil. Para isso seriam disponibilizados, na plataforma, diversos treinamentos no qual o funcionário poderia ser designado a estudar.

[GIT](https://github.com/giovannialves01/API-RGBA) 


#### Tecnologias Utilizadas

-Javascript: Linguagem utilizada em páginas web para codificar funções como mensagens de alerta que foram utilizadas para funcionalidades adicionais no front.

-Spring: Inicializador utilizado para criar projeto já com várias dependências que utilizaríamos.

-CSS3: Linguagem que permitiu criar os visuais que apareceriam na tela para o usuário.

-HTML5: Linguagem utilizada para codificar as telas do Front-End.

-PostgreSQL: Banco de dados relacional, utilizado para o armazenamento das informações dos cursos, alunos e professores.

-Java: Linguagem orientada a objeto utlizada para a construção do Back-End do projeto.


#### Contribuições Pessoais
Nessa API eu participei de 4 funcionalidades principais.

1-Criação da pagina de Log

No Back-End...

-Um arquivo Java Script foi criado para armazenar os atributos de um log como resposta e entidades.

-Um laço for irá analisar todas as logs existentes e alimentar as variáveis com as informações encontradas através do textcontent, que, a partir do texto determinado, trará a informação a frente deles.
 
-A sessão de valor, por sua vez, trará o identificador de cada informação.

-O script adicionado no front possui os métodos de criação e importação dos conteúdos das logs com base no banco de dados, isso foi feito através de um constructor.
  
-Caso o valor não seja encontrado, dados genéricos são enviados.
  
-O constructor utilizara dos métodos get para obter as informações, enquanto as set serão utilizadas para a criação das logs.


No Front-End...

-Foi preciso adicionar o script do log em sua respectiva pagina para que seus métodos pudessem ser utilizados.

-Log significa registrar quaisquer acoes que afetaram o sistema com data e hora dessas acoes.
 
-Para isso servira a div log, exibit as atividades e modificações feitas por usuários assim como quando eles fizeram isso.

-Enfim, pode-se adicionar o serviço de log na tela de administrador.

-Para isso, inicialmente, é preciso chamar o script do log.js.

-Com o script declarado, pode-se informar o usuário que os Logs estão disponíveis a baixo e criar a div que exibirá as logs.


2-Adição do Chatbot

-Como o chatbot se tratava de um serviço externo, bastava com que fosse adicionada, nas paginas necessárias, a estrutura de código apropriada para "chama-lo". As páginas onde o chatbot se encontra são as paginas de...

-Turmas do Tutor
-Página do Aluno
-Página Minha Conta
-Página Meus Cursos
-Página Gestor
-Página de Detalhes do Curso
-Catálogo de Cursos


3-Atualização do Header
Para que essa funcionalidade do header fosse implementada, inicialmente, devia-se criar seu estilo na página de css, ou seja, tecnologia utilizada para criação dos visuais na tela. Estilos esses que incluem, mas não se limitam a tamanho do header (width: 300px; height: 300px;), margem do texto do título (margin-left: 20px;) etc.

Por fim, para verificar a funcionalidade do header, esse foi adicionado a página de notícias assim como um texto base.

4-Criação da página de notícias

Por fim, para a programação da página onde o usuário encontraria as notícias da plataforma, deveria criar a celula head com informações como o título da página e conjunto de caracteres a serem utilizados.

O body das novidades, assim como suas divs, foi criado como placeholder para que o grupo pudesse ter noção de onde cada funcionalidade se encontraria na versão final. Nele, é possível ver a definição do estilo das imagens, como tamanho da borda (border: 1px solid gray), margem entre outros elementos da tela (margin: 10px) e tamanho dos elementos (height: 150px; width).

O restante da página contém comentários que mais tarde serviram para incorporar outras funcionalidades na página como lista de cursos, bibliotecas, questionários etc.

#### Hard Skills 
Java - Sei fazer com autonomia.

PostgreSQL - Sei fazer com autonomia.


#### Soft Skills
Humildade - Em diversos momentos me deparei com situações onde eu deveria usar métodos que eu não conhecia e me vi na necessidade de pedir ajuda aos demais colegas de equipe.

Comunicação Interpessoal - Por me encontrar varias vezes necessitando de ajuda, era necessário comunicar propriamente minhas dificuldades e garantir que eu já tinha feito tudo o que estava ao meu alcance para resolver antes de pedir auxílio.

### Em 2021-2
O quarto API teve como parceira a Empresa Brasileira de Aeronáutica - EMBRAER. O cliente enfrentava dificuldades com seu sistema de armazenamento de arquivos pois esses deveriam ter nomes e armazenamentos padronizados. Tendo isso em vista, a equipe Sirius desenvolveu um aplicativo web onde o usuário poderia fazer upload dos arquivos(desde que toda a formatação oficial fosse seguida), armazena-los e permitir com que o download desses fosse feito posteriormente.

[GIT](https://github.com/giovannialves01/Sirius) 

![image](https://user-images.githubusercontent.com/65372142/170794184-daf477d0-35b6-4731-aa43-00088d7e2071.png)

Tecnologias Utilizadas:

-Java: Utilizada para a programação do back-end
-Javascript: Utilizado para pequenas operações no front-end como exibição de avisos
-HTML: Linguagem para criação das telas do projeto
-Springboot: Inicializados do projeto em formato Maven
-Postgre: Banco de dados utilizado para armazenar informações sobre os documentos

Contribuições Pessoais

-Conversão para PDF:

A conversão para pdf e necessária tendo em vista a formatação oficial do nosso cliente, ou seja, caso fosse feito upload de um arquivo docx, este deveria estar disponível no formato pdf. O método para a conversão foi adicionado no sistema de download de arquivo pois como o sistema de conversão utilizado não substitui, apenas cria uma cópia no formato correto, foi julgado ideal inclui-lo no sistema de download para economizar espaço de disco. Quando o download e feito, todos os documentos que possuem o nome desejado são convertidos para pdf através de um método que cria copias em pdf desses arquivos na pasta desejada, e então esses mesmos arquivos são unificados em um. Dessa forma, independente do formato que o usuário faça upload do documento, sempre que for necessário seu download, este estará disponível no formato pdf.

-Confirmação de nome dos documentos: Durante o processo de upload dos documentos, inclui um código que analisa cada parte do nome do documento, caso não obedeça as padronizações mencionadas, o upload é cancelado e o usuário é informado de que deve arrumar o nome do documento.

A padronização do nome do documento funciona da seguinte forma:

Nome: Nesse momento o controller do upload de arquivos verifica se o nome possui 8 caracteres, sendo que os 3 primeiros devem conter apenas letras de A a Z, o quarto caractere deve ser um hífen e os 4 caracteres restantes devem ser apenas números de 0 a 9

Section: Controller analisa se esse constitui de letras ou números, apenas isso é o suficiente para aprovação.

Subsection: É feita uma análise para saber se este constitui apenas de números, caso seja, é aprovado.

Bloco: É feita uma análise para saber se este constitui apenas de números, caso seja, é aprovado.

Todos esse métodos possuem a própria variável de aprovação que pode ser verdadeira ou falsa. Caso algum dos elementos do nome do documento não esteja na padronização, sua respectiva variável será atribuída o valor falso o que enviará uma mensagem de erro para o front-end, mensagem essa que informará o usuário que as informações que inseriu estão incorretas. Se não houver nenhuma reprovação o arquivo é armazenado e o usuário é informado que a a operação foi um sucesso.

-Teste Estrutural:

A parte de teste estrutural foi feita como validação para a matéria de Testes de Software, onde era necessário que uma classe de teste fosse utilizada para testar uma funcionalidade do projeto.

Para isso, resolvi testar a função de validação do nome do documento da classe FileUploadController(comentada a pouco), já que essa funcionalidade foi criada por mim. A classe de teste envia para a classe de upload valores de nomes de documentos, de cada nome era esperado sucesso ou falhar. Exemplo:
 Caso o nome "Abc-1234-a1-00-11" fosse aceito, o teste era um sucesso, pois esse tipo de formato no nome do documento é o correto.
 Caso o nome "FFFF-333-a1-aa-bb" fosse recusado, o teste era um sucesso pois esse nome está fora da formatação.

-Notificação de sucesso ou falha:

 Na tela de upload do aplicativo, há um script esperando uma resposta do controller do upload de arquivos. Caso o upload seja um sucesso, o controller enviará a informação "ok" ou "error" através do model. Recebido esse model, o front analisará qual das opções recebeu, caso receba ok, informará, através de uma notificação que o upload foi um sucesso, do contrário, informara que ocorreu um erro e informará que o usuário deve verificar o nome do documento e verificar que deve condizer com a formatação oficial.

Hard Skills

PostgreSQL-sei fazer com autonomia.
Java-sei fazer com autonomia.

Soft Skills

Perseverança: como não conseguimos validar as 2 primeiras entregas, precisamos nos dedicar ao máximo para validar as 2 últimas.
Autonomia: como cada membro do time se ocupou com uma tarefa, muitas vezes a entrega de uma funcinalidade dependia exclusivamente de mim sem poder contar com ajuda de terceiros.



### Em 2022-1
O primeiro projeto de API a ser feito apos EAD teve como empresa parceira, novamente, a Embraer. A necessidade dessa vez envolvia o armazenamento de documentos chamados FOLs(documentos referentes as aeronaves adquiridas pelo usuário) assim como notificação dos usuários do aplicativo que novos documentos haviam sido criados. Para isso nossa equipe desenvolveu o aplicativo Brisk, que permitiria com que os usuários visualizassem as FOLs de qualquer uma de suas aeronaves e ainda geraria relatórios de quantos usuários visualizaram esses documentos.

[GIT]([https://github.com/AirghostTeamAPI]) 

![image](https://user-images.githubusercontent.com/65372142/171982689-6b84e7a9-3944-43dc-9a27-0ab96c1e2935.png)

Tecnologias Utilizadas
Java script: Utilizado para a construção do Front-End, ou seja, as telas que o usuário utilizaria para navegar pelo aplicativo
Typescript: Construção do Back-End com todas as requisições de cadastros, notificações e movimentação dos documentos
Node.js: Permitiu execução dos códigos em Java script independente se estivesse no navegador web, muito útil tendo em vista que deveria ser executável tanto na página web quanto no aplicativo
React Native: Estrutura principal de construção das telas
MongoDB: Banco de dados utilizado para armazenamento das informações de usuários e FOLs

Contribuições pessoais

Login de Usuário

O login foi feito na classe index.js da pasta login do nosso back end. Primeiramente o usuário deve inserir suas credenciais de login e senha e pressionar o botão de login que buscara no banco de dados se esse usuário existe, permitindo sua entrada caso afirmativo e proibindo sua entrada caso contrário. Nessa mesma tela e criado um token para o usuário que armazenara informações como o fato de ter feito login e as notificações que recebera. 

Leitura de PDF
A página de exibição de pdf possui um método de retorno que exibira a FOL que o usuário deseja, para isso e necessário retornar uma página especifica de um documento

Com o uso de funções Axios serão retornados opções de mostrar as todas as FOLs de um usuário assim como filtrar de acordo com sua categoria ou palavras chaves referentes a seu conteúdo

Finalmente, a função returno servira para retornar o PDF na pagina da FOL desejada pelo usuário no for

Gráfico de Alcance das FOLs
O gráfico foi feita armazenando, em variáveis, informações do banco de dados obtidas através de uma rota do axios, variáveis essas que se tratam de quantidade de usuários notificados da criação de uma FOL e usuários que leram essa notificação. Essas, em seguida, são enviadas para um retorno em js que construirá um gráfico com informando a quantidade de usuários que leram a informacao e a quantidade de usuários que não leram(feito através da diferença entre total de usuários que receberam a notificação e o total de usuários que leram)

### Em 2022-2
Mesmo formato 

## Meus Principais Conhecimentos
-Análise e Armazenamento de Dados.
Área da tecnologia do qual sempre tive afinidade e também muitos contatos que poderiam me auxiliar. Matéria na qual mais me destaquei durante o Médio Técnico.

-Tecnologia de Chatbot.
Projeto do qual mais me destaquei no meu primeiro estágio. Requereu muito do meu conhecimento de banco de dados para construção de árvores de decisão. Apresentei, na FATEC, uma palestra com esse tema, inclusive.

-Linguagem Java. 
Primeira linguagem nova que eu aprendi após 3 anos de C# e que me foi muito útil em diversos projetos da faculdade.

Hard Skills

PostgreSQL-sei fazer com autonomia.
Java-sei fazer com autonomia.

Soft Skills

Perseverança: como não conseguimos validar as 2 primeiras entregas, precisamos nos dedicar ao máximo para validar as 2 últimas.
Autonomia: como cada membro do time se ocupou com uma tarefa, muitas vezes a entrega de uma funcinalidade dependia exclusivamente de mim sem poder contar com ajuda de terceiros.
  
## Contatos
* [GIT](https://github.com/Felipe-Silva2002 | https://github.com/Ffelipe-Ssilva)
* [LinkedIn](https://www.linkedin.com/in/felipe-silva-13b3b61a0)

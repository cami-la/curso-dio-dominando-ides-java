<h1>Dominando IDEs Java </h1>

<p> Sejam bem-vindos ao curso <strong>DOMINANDO IDEs JAVA</strong> oferecido gratuitamente pela plataforma de cursos online <a href="https://web.digitalinnovation.one/"><strong> Digital Innovation One</a></strong>. 🧡💛<br>

<div align="center">	
▶️ <a href="https://www.youtube.com/watch?v=wcIm916zk9w&lc=UgwDmJkoCf5M9Pf66ll4AaABAg">Como criar um Access Token para se conectar com o GitHub</a></div>
	
<h2> 🚦 Guia </h2>

<p>
🔹 Começaremos passando rapidamente sobre o Java e algumas das suas características mais importantes <br>
🔹 Em seguida, entraremos nas instalações do Java e das IDEs nos diferentes sistemas operacionais: Windows e Linux<br>
🔹 E seguiremos até o final do curso explicando de uma forma leve e objetiva sobre umas das IDEs mais conhecidas para desenvolvimento Java: Eclipse IDE e IntelliJ IDEA IDE <br>
</p>    
<p align="center"> <em> ⚠️ Lembrando que o <strong>foco do curso são as IDEs</strong> e não a linguaguem Java. Ok? ⚠️ </em></p>



<h2>
🛑 Pré-requistos
</h2>


- [x] Sistema operacional (Windows e/ou Linux)

- [x] Conta no GitHub

  

<h2> 📚 Ementa</h2>

<h3><strong>▪️ Instalação/Configuração do Java</strong></h3>

✅ Um pouco da história do Java<br>✅ Diferença entre JRE e JDK<br>✅ Versões do Java<br>
✅ Se não existisse IDE?<br>

<h3><strong> ▪️ Ubuntu</strong></h3>

✅ Instalação OpenJDK <br>✅ Configuração de variável de ambiente<br>✅ Instalação do Eclipse<br>✅ Configurando o ícone no Dock<br>✅ Instalação do IntelliJ<br>

<h3><strong> ▪️ Windows</strong></h3>

✅ Instalação OpenJDK<br>✅ Configuração de variável de ambiente<br>✅ Instalação do Eclipse<br>✅ Instalação do IntelliJ<br>

<h3><strong> ▪️ IntelliJ </strong></h3>

✅ Diferenças entre versões<br>✅ Conhecendo um pouco por dentro da IDE<br>✅ Criando seu primeiro projeto Java no IntelliJ<br>✅ Atalhos e Produtividade<br>✅ Conectar seu projeto no GitHub<br>

<h3><strong> ▪️ Eclipse </strong></h3>

✅ Diferenças entre versões<br>✅ Conhecendo um pouco por dentro da IDE<br>✅ Criando seu primeiro projeto Java no IntelliJ<br>✅ Atalhos e Produtividade<br>✅ Conectar seu projeto no GitHub<br>

<h3><strong> ▪️ Outras Alternativas </strong></h3>

✅ Visual Studio Code<br>

<br><br>


<h2><strong> 🐧 LINUX</h2></strong>

<h3>🔺 Instalação OpenJDK</h3>

<em><strong>O OpenJDK (Kit de Desenvolvimento Java Aberto)</strong> é uma  implementação gratuita e de código aberto da linguagem de programação  Java.  A implementação está licenciada sob a GNU General Public License  (GPL) com uma exceção de vinculação. <strong>JDK = JRE + JVM</strong></em>

🔸 <strong>1.</strong> Abra o terminal e vamos verificar se temos o Java instalado:

```
java -version
```

🔸 <strong>2.</strong> Para instalar o openJDK-11, digite no terminal:
<em>A versão mais atual LTS é do Java 11, que terá seu suporte  estendido até Setembro de 2022. Este tipo de suporte iniciou no Java 8  que será mantido até 2023.</em>

```
sudo apt-get install openjdk-11-jdk
```

🔸 <strong>3.</strong> Confirme se realmente foi instalado com sucesso:

```
java -version
```

🔸<strong>4.</strong> Vamos configurar o ambiente JAVA_HOME:

​	<strong>4.1</strong> Verificar o caminho da instalação do Java:

```
sudo update-alternatives --config java
```

​	<strong>4.2</strong> Copie o caminho que aparecerá no terminal, no meu caso:

```
/usr/lib/jvm/java-11-openjdk-amd64/bin/java
```

​	<strong>4.3</strong> Vamos editar o arquivo .bashrc:

```
sudo gedit ~/.bashrc
```

​	<strong>4.4</strong> Copie o código abaixo e cole no final do arquivo .bashrc. 

​	<em>IMPORTANTE: cuidado para não alterar nada no arquivo além de apenas colar no final do mesmo o que vou te disponibilizar a seguir. </em>

​	<em>JAVA_HOME = aqui você coloca o caminho do tópico 4.2, tirando o /bin/java</em>

```
JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export JAVA_HOME
export PATH=$PATH:$JAVA_HOME
```

​	<strong>4.3</strong> Salve o arquivo

​	<strong>4.4</strong> Vamos conferir se a alteração ficou salva:

```
cat ~/.bashrc
```

🔸<strong>5.</strong>  Feche o terminal e abra novamente

🔸<strong>6.</strong> Vamos conferir mais uma vez se o Java está instalado na nossa máquina

```
java --version
```

<p align="right"><em>Créditos: <a href="https://www.youtube.com/watch?v=jARiy3DZdwg">DevSuperior</a></em></p>

<br>

<h3>🔺 Instalação Eclipse </h3>

🔸 <strong>1.</strong> Entre no site oficial do Eclipse Foundation e faça o <strong><a href="https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2021-06/R/eclipse-inst-jre-linux64.tar.gz">DOWNLOAD</a></strong>
<em>O site já identifica o sistema operacional.</em>

🔸 <strong>2.</strong> Descompacte a pasta

🔸 <strong>3.</strong> Procure o arquivo eclipse-inst e execute

🔸 <strong>4.</strong> Escolha segunda a opção: Eclipse IDE for Enterprise Java and Web Developers

🔸 <strong>5.</strong> Clique no folder da primeira opção e selecione o JDK que instalamos na nossa máquina.

🔸 <strong>6.</strong> Mantenha as opções "create start menu entry" e "create desktop shortcut"

🔸 <strong>7.</strong> Install

🔸 <strong>8.</strong> Accept now

🔸 <strong>9.</strong> Launch

🔸 <strong>10.</strong> Pronto, intalação concluída!

<br>

<h3>🔺 Configurando o ícone do Eclipse IDE no Dock </h3>

<br>

<h3>🔺 Instalação IntelliJ IDEA Community </h3>

🔸 <strong>1.</strong> Entre no site ofical do <a href="https://www.jetbrains.com/idea/download/#section=windows"><strong>INTELLIJ</strong></a>

🔸 <strong>2.</strong> Escolha a opção Community e faça o download 

🔸 <strong>3.</strong> Descompacte a pasta e vamos para o terminal

🔸 <strong>4.</strong> Abra o terminal (Ctrl + Alt +  t) e entre no diretório que você descompactou 
<em>No meu caso, na pasta Downloads Ideal</em>

```
cd Downloads/IdealC
```

🔸 <strong>5.</strong> Entre na pasta bin

```
cd bin
```

🔸 <strong>6.</strong> Execute o arquivo de instalação idea.sh

```
./idea.sh
```

<br>

<h3>🔺 Instalação Git </h3>

🔸 <strong>1.</strong> Abra o terminal (Ctrl + Alt + t) e vamos verificar se temos o git instalado:

```
git --version
```

🔸 <strong>2.</strong> Execute o comando:

```
sudo apt-get install git-all
```

🔸<strong>3.</strong> Confirme novamente se o git realmente está instalado:

```
git --version
```

🔸 <strong>4.</strong> Vamos começar as configurações iniciais:

​	<strong>4.1</strong> Cofigurar o nome de usuário

```
git config --global user.name "Seu nome"
```

​	<strong>4.2</strong> Configurar o endereço de e-mail:
​	<em>É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!</em>

```
git config --global user.email seuemail@email.br
```

​	<strong>4.3</strong> Vamos conferir a lista de configurações:

```
git config --list
```

🔸 <strong>5.</strong> Pronto, git instalado e configurado com sucesso!

<br><br>

<h2><strong>🪟 WINDOWS</h2></strong>

<h3>🔺 Instalação JDK Zulu</h3>

Aqui no windows, vamos fazer o download do <strong>OpenJDK Zulu</strong>.
<em>As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.</em>

🔹 <strong>1.</strong> Entre no <a href="https://www.azul.com/downloads/?package=jdk"><strong>SITE AZUL</strong></a>

🔹 <strong>2.</strong> Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit

🔹 <strong>3.</strong> Vá no drive C://Arquivo de Programas

🔹 <strong>4.</strong> Caso não tenha um diretório com o nome Java, crie

🔹 <strong>5.</strong>  Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

🔹 <strong>6.</strong> Vamos configurar o ambiente JAVA_HOME:

​	<strong>6.1</strong>  Menu iniciar -> Editar as varáveis de ambiente do sistema

​	<strong>6.2</strong> Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente

​	<strong>6.3</strong> Na janela Variáveis de Ambiente,  crie um novo Variáveis do sistema

​	<strong>6.4</strong> Abrirá uma jabela: Nova Variável de Sistema.

​	<strong>6.5</strong> Nome da variável: JAVA_HOME

​	<strong>6.6</strong> Valor da variável: em seguida OK.
​	<em>O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo 5 </em>

​	<strong>6.7</strong> Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...

​	<strong>6.8</strong> Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin

​	<strong>6.9</strong> Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo

🔹 <strong>7.</strong> Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho

🔹 <strong>8.</strong> Abra o Prompt de Comando: Menu iniciar -> cmd

🔹 <strong>9.</strong> Vamos conferir mais uma vez se o Java está instalado na nossa máquina

```
java -version
```

<p align="right"><em>Créditos: <a href="https://www.youtube.com/watch?v=laC0fiI-IOM">DevSuperior</a></em></p>

<br>

<h3>🔺 Instalação Eclipse </h3>

🔹 <strong>1.</strong> Acessar o site oficial do <a href="https://www.eclipse.org/downloads/"><strong>ECLIPSE</strong></a>

🔹 <strong>2.</strong> Fazer o download do instalador

🔹 <strong>3.</strong> Escolha segunda a opção: Eclipse IDE for Enterprise Java and Web Developers <a href="https://www.eclipse.org/downloads/packages/"><strong>Link de download para Windows</strong></a>

🔹 <strong>4.</strong> Clique no folder da primeira opção (Java 11 + VM) e selecione o JDK que instalamos na nossa máquina

🔹 <strong>5.</strong> Mantenha as opções "create start menu entry" e "create desktop shortcut"

🔹 <strong>6.</strong> Install

🔹 <strong>7.</strong> Accept now

🔹 <strong>8.</strong> Launch

🔹 <strong>9.</strong> Pronto, intalação concluída

<br>

<h3>🔺 Instalação IntelliJ IDEA Community </h3>

🔹 <strong>1.</strong> Entre no site ofical do <a href="https://www.jetbrains.com/idea/download/#section=windows"><strong>INTELLIJ</strong></a>

🔹 <strong>2.</strong> Escolha a opção Community e faça o download 

🔹 <strong>3.</strong> Siga com next

🔹 <strong>4.</strong> Na opção Installation Options, deixe selecionado as opções:
	<strong>4.1</strong> 64-bit launcher (caso seu sistema seja 64-bit, caso não, selecione 32-bit)
	<strong>4.2</strong> Add "Open Folder as Project"
	<strong>4.3</strong> .java - .groovy - .kt - .kts
	<strong>4.4</strong> Add lauchers dir to the PATH
	<strong>4.5</strong> Next

🔹 <strong>5.</strong> Install

🔹 <strong>6.</strong> Para finalizar a instalação, escolha a opção reebot later

🔹<strong>7.</strong> Com o IntelliJ já instalado, vamos iniciar:

​	<strong>7.1</strong> Aceite os termos: I confirm that I have... >> Confirm

​	<strong>7.2</strong> Data Sharing >> Send Anonymous Statistics

🔹<strong>8.</strong> IDE pronta para uso!

<br>

<h3>🔺 Instalação Git </h3>

🔹 <strong>1.</strong> Entre no site ofical do <a href ="https://git-scm.com/downloads"><strong>GIT</strong></a>

🔹 <strong>2.</strong> Escolha a opção Windows e o instalador será baixado automáticamente

🔹 <strong>3.</strong> Mantenha as opções pré selecionadas e siga com Next

🔹 <strong>4.</strong> Install

🔹 <strong>5.</strong> Antes de finaizar a instalação, selecione a opção Lauch Git Bash 

🔹<strong>6.</strong> Ao finalizar o passo 5, irá abrir o Git Bash

🔹<strong>7.</strong> Agora vamos fazer as configurações iniciais:

🔹<strong>8.</strong> Confirme se o git realmente está instalado:

```
git --version
```

🔹<strong>9.</strong> Vamos começar as configurações iniciais:

​	<strong>9.1</strong> Configurar o nome de usuário

```
git config --global user.name "Seu nome"
```

​	<strong>9.2</strong> Configurar o endereço de e-mail:
​	<em>É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!</em>

```
git config --global user.email seuemail@email.br
```

​	<strong>9.3</strong> Vamos conferir a lista de configurações:

```
git config --list
```

🔹<strong>10.</strong> Pronto, git instalado e configurado com sucesso!

<br><br>

<h2> 🤝 Contribuindo </h2>

Este repositório foi criado para fins de estudo, então contribua com ele.
Se te ajudei de alguma forma, ficarei feliz em saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.

Se possível:

⭐️  Star o projeto

🐛 Encontrar e relatar issues


------------

Disponibilizado com ♥ por [cami-la](https://www.linkedin.com/in/cami-la/ "cami-la").


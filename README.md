<h1 align="center">React Native</h1> 
Here is my study on React Native, based on Alura's course.

<h1>Começando</h1>
<p>Para iniciarmos nossa trajetória em React Native, é necessário aprendermos ao menos o básico do Javascipt, tenho um repositório do meu estudo de na linguagem, <a href="https://github.com/gotomarcelo/aprendendo-js/blob/master/README.md" target="_blank">clique aqui</a>.</p>

<p>Vamos dar uma olhada no site do <a href="https://reactnative.dev" target="_blank">React Native</a>.</p>
<p>E vamos olhar como instalar o ambiente de trabalho -> <a href="https://reactnative.dev" target="_blank">Enviroment Setup</a>.</p>

<h2>Primeiramente, o que é React Native?</h2>
<p>React Native é uma framework do JavaScript para programar aplicações nativas e reais tanto para IOS quanto para Andriod. Ela é baseada na biblioteca do Meta, o React. Ou seja é uma framework que mira nos dispositivos móveis para criação de aplicativos. E o mais legal de tudo é que o mesmo código funciona para ambos os sistemas operacionais móveis.</p>

<h2>Caldeirão de tecnologias e linguagens:</h2>
<p>Dentro do framework, temos o Javascript, o React, o JSX, XML. E debaixo do tapete, temos uma renderização para Objective-C (IOS) e Java (Android), na qual o React Native transforma o nosso código em uma dessas duas linguagens, e fazendo uma aplicação real que pode usar os componentes do dispositivo (cameras, microfones...).</p>

<h2>Ambiente de trabalho:</h2>
<p>Para configuração de ambiente de trabalho em Mac, é necessário fazer o ambiente para isso, e o mesmo equivale para windows/linux para Android.</p>
<p>Existe o Expo CLI, que é uma forma de não precisar configurar o ambiente de trabalho sem ter instalação e configuração. E outra coisa legal é que a atualização é feita de forma automática assim que é atualizado em nosso código.</p>
<p>Mas existem limitações, alguns recursos não tem no Expo e temos aplicações de nível maior, pois o Expo demanda que o código nativo já esteja no aplicativo base.</p>

<h1>Configurando o Expo</h1>
<p>O Expo é um pacote do node, então primeiramente precisamos instalar o Node, nesse <a href="https://nodejs.org/en/" target="_blank">link</a>.
<br/>
Após a instalação, no terminal, temos como verificar se deu tudo certo escrevendo:
</p>

```console
node --version
```

<p>Após o Node instalado, agora vamos para o Expo:</p>

```console
npm i -g expo-cli
```

> É importante também atualizar os pacotes `deprecated`

<p>E para visualizar sua futura aplicação no seu dispositivo, baixe o aplicativo Expo na loja de aplicativos.</p>

<h1>Iniciando o projeto</h1>
<p>Para iniciar o projeto, basta no terminal digitar:</p>

```console
expo init nomeDoProjeto
```

Entre na pasta do seu projeto:

```console
cd nomeDoProjeto
```
E inicie o react:

```console
npm start
```
Aparecerá o QR code, abra no seu app do expo go.

> Caso esteja usando uma outra internet no celular, configure no localhost criado, como tunnel, assim a aplicação irá passar via internet.

E agora podemos programar nosso aplicativo!

<h1>Programando</h1>

O ReactNative e o Expo tem a live reload, no qual ele atualiza automaticamente assim que é feito uma alteração no programa, mas para casos de adicionar uma biblioteca, talvez seja necessário atualizar manualmente.

É notório comentar que usando o expo ficamos limitados a algumas features, como não poder usar o bluetooth, WebRTC, compras integradas, audio de fundo ao sair do app, algumas bibliotecas nativas proprietárias, tamanho máximo de assests é de 50MB e entre outros.

<h2>Criando um componente:</h2>
Assim como React, vamos criar componentes para utilizar em nossa aplicação:

<li>Crie um novo arquivo NomeComponente.js</li>


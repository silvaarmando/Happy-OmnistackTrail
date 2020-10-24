<h1 style="font-size: 50pt"><img src="logo-main-happy.png"> HAPPY </h1>

### A Aplicação Happy foi desenvolvida pela **[Rocketseat](https://rocketseat.com.br/)** no 3° Workshop da **NLW (Next Level Week)**
### Happy é uma aplicação que cadastra e lista orfanatos para receber visitas para as crianças.

#### Principais ferramentas:
* A aplicação é desenvolvida usando a stack **[NodeJS](https://nodejs.org/en/)** com **[TypeScript](https://www.typescriptlang.org/)**
* **[ReactJS](https://pt-br.reactjs.org/)** para a aplicação Web, **[React Native](https://reactnative.dev/)** e **[Expo](https://expo.io/)** para aplicação Mobile.
* e o **[Yarn](https://yarnpkg.com/)** como gerenciador de pacotes do NodeJS e para o banco de dados iremos utilizar **[SQLite](https://www.sqlite.org/index.html)**.

<img src="https://camo.githubusercontent.com/ab047aab3d605de3382a853eeeebc583dd37890d/68747470733a2f2f64657669636f6e732e6769746875622e696f2f64657669636f6e2f64657669636f6e2e6769742f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667" width="35" height="35"><img src="https://camo.githubusercontent.com/4683d18a4a9f845dd7de377a6915dcfc9739a661/68747470733a2f2f64657669636f6e732e6769746875622e696f2f64657669636f6e2f64657669636f6e2e6769742f69636f6e732f72656163742f72656163742d6f726967696e616c2d776f72646d61726b2e737667" width="35" height="35"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/512px-Typescript_logo_2020.svg.png" width="35" height="35"><img src="https://cdn.icon-icons.com/icons2/2389/PNG/512/expo_logo_icon_145293.png" width="35" height="35"><img src="https://seeklogo.com/images/Y/yarn-logo-F5E7A65FA2-seeklogo.com.png" width="35" height="35">

## PROGRESSO DO EVENTO

✅ 1° DIA - Vimos a apresentação do projeto, o layout e os principais conceitos sobre back-end, front-end e API, a criação da nossa landing page em **ReactJS**, criação das rotas para navegar entre os arquivos, a criação da página com o mapa.
<br>
✅ 2° DIA - Criamos um projeto com **NodeJS**, criamos o back-end da aplicação e nosso banco de dados com SQLite.
</br>
✅ 3° DIA - Finalizamos nossa página de mapa, criamos navegação entre telas, conectamos front-end com back-end e Finalizamos todo o nosso front-end web. 
</br>
✅ 4° DIA - Aprendemos sobre os principais conceitos do **React Native** e do **Expo**, criação da onboarding, criação de rotas e criação da tela de mapas. 
</br>
✅ 5° DIA - Finalizamos o App Mobile com a listagem e cadastro de orfanatos.

##  BACKEND

A nossa API Rest será construida no padrão [MVC](https://pt.wikipedia.org/wiki/MVC):

**MODEL**: respresentação de uma tabela no banco, representatividade de uma entidade na nossa aplicação.

**VIEW**: é como as coisas são vistas pelo nosso frontend.

**CONTROLLER**: é a lógica das rotas na nossa aplicação.

### Para iniciarmos a desenvolver o desenvolvimento da aplicação backend precisamos iniciarmos o yarn:

   **```yarn init -y```**

### Lista das Principais Ferramentas utilizadas

- **[TypeScript](https://www.typescriptlang.org/)** para adicionar tipagem e algumas outras funções ao nosso código.

   **```yarn add typescript -D```**

- **[Express](https://expressjs.com/pt-br/)** para criarmos nosso servidor em NodeJS.

   **```yarn add express```**

   **```yarn add @types/express```**

- **[TS-Node-Dev]()** para monitorarmos nosso servidor.

   **```yarn add ts-node-dev```**

- **[multer](https://github.com/expressjs/multer)** utilizado principalmente para carregamento de arquivos.

   **```yarn add multer```**

   **```yarn add @types/multer```**

- **[typeorm](https://www.npmjs.com/package/typeorm)** utilizamos como orm (mapeador objeto relacional) nesse projeto.

   **```yarn add typeorm```**

- **[SQLite](https://www.sqlite.org/index.html)** como sistema de banco de dados.

   **```yarn add sqlite3```**

- **[Yup](https://www.npmjs.com/package/yup)** para validação de formularios.

   **```yarn add yup```**

   **```yarn add @types/yup```** 

### Utilizamos o **[Insomnia](https://insomnia.rest/download/)** para fazer testes no nosso backend

![](happy-orphanages-backend.gif)

## FRONTEND WEB

O nosso frontend web foi desenvolvido em ReactJS que utiliza o Single Page Application ou [SPA](https://pt.wikipedia.org/wiki/Aplicativo_de_p%C3%A1gina_%C3%BAnica), que em português significa Aplicações de página única,foram vistos os conceitos principais sobre como React, componentização e propriedades de elementos, para iniciarmos nosso projeto com **yarn** em typescript precisamos instalar o react:

   **```yarn create react-app web --template typescript```**

### Lista das principais ferramentas utilizadas na construção do sistema web:

- **[React Dom](https://pt-br.reactjs.org/docs/react-dom.html)** é usado para manipular elementos HTML.

- **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)** é utilizado para criar um sistema de routeamento no ReactJS:

   **```yarn add react-router-dom```**

   **```yarn add @types/react-router-dom```**

- **[Leaflet](https://leafletjs.com/)** para lidar com mapas no **ReactJS**.

   **```yarn add leaflet, react-leaflet```** 

   **```yarn add @types/leaflet```**

- **[React Icons](https://react-icons.github.io/react-icons/)** para adicionar icones.

   **```yarn add react-icons```**

- **[Axios](https://github.com/axios/axios)** como cliente HTTP.

   **```yarn add axios```**

##### Aplicação Web com todas as funcionalidades dessa versão: 

![](happy-web-front-end.gif)

## FRONTEND MOBILE

O Frontend Mobile foi desevolvido desenvolvido usando React Native com Expo, o React Native é uma biblioteca Javascript criada pelo Facebook. É usada para desenvolver aplicativos para os sistemas Android e IOS de forma nativa.

### Instalação do Expo:

   **```yarn global add expo-cli```**

### Para executar a aplicação: 

   **```yarn start```**

- **[Expo-google-fonts/nunito](https://github.com/expo/google-fonts)** para utilizarmos uma fonte de texto personalizada, no caso vamos utilizar a fonte [Nunito](https://fonts.google.com/specimen/Nunito?query=Nunito).

   **```yarn add @expo-google-fonts/nunito```**

- **[React-native-maps](https://github.com/react-native-maps/react-native-maps)** para lidarmos com mapas dentro do nosso aplicativo.

   **```expo install react-native-maps```**

- **[React Navigation](https://reactnavigation.org/)** para trabalhar com navegação entre telas.

   **```yarn add @react-navigation/native```**

- **Instalando dependências de um projeto gerenciado comm Expo**

   **```expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view```**

- **Instalando dependências em um projeto nativo de reação nu**

   **```yarn add react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view```**

- **[expo-image-picker]()** para ter acesso a interface do sistema para trabalhar com imagens dentro do React Native.

   **```expo install expo-image-picker```** 
   
- **[axios](https://github.com/axios/axios)** para conectar o mobile com o nosso servidor.

   **```yarn add axios```**

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<img src="happy-frontend-mobile.gif" style="justify-content: center">


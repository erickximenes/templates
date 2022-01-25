<div id="inicio"></div>

## 📱 {{nome do repositorio}}

> Projeto desenvolvido em Flutter e utilizando o pacote firebase-tools do npm, com a finalidade de criar um website exemplo.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
* Você instalou a versão mais recente do `NodeJS`
* Você instalou a versão mais recente do `Flutter`
* Você tem uma máquina `Windows`. O código não foi testado em `Linux` e `MacOS`.

## 🚀 Instalando {{nome do repositorio}}

Para instalar o {{nome do repositorio}}, siga estas etapas:

Linux e macOS:
```
npm install -g firebase-tools
```

Windows:
```
npm install -g firebase-tools
```


## 👨‍💻 Obter FIREBASE_TOKEN para por no actions

```
npx firebase login:ci
```

Copiar o token que recebeu no terminal. Depois ir na página do repository no Github > Settings > Secrets > New repository secret.

```
NAME: FIREBASE_TOKEN
VALUE: SEU TOKEN
```


## ☕ Usando {{nome do repositorio}}

### Para iniciar o projeto no firebase, siga estas etapas:

```
npx firebase login
```

```
npx firebase init
```

```
npx firebase deploy --only hosting
```

### Para subir o projeto para o firebase, siga estas etapas:

```
npx firebase deploy --only hosting
```

### Para usar website, siga estas etapas:

```
flutter run
```


## 🤝 Colaborador

Agradecemos à seguinte pessoa que contribuiu para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/erick-vasconcelos-50baa8150/" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/67069017?v=4" width="100px;" alt="Foto do Erick no GitHub"/><br>
        <sub>
          <b>Erick Vasconcelos</b>
        </sub><br>
        <a href="https://www.buymeacoffee.com/erickzaunlab" target="_blank"><img src="https://raw.githubusercontent.com/appcraftstudio/buymeacoffee/master/Images/snapshot-bmc-button.png" width="100px;"></a>
      </a>
    </td>
  </tr>
</table>


[⬆ Voltar ao topo](#inicio)<br>

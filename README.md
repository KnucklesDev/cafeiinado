<img src="https://i2.wp.com/allhtaccess.info/wp-content/uploads/2018/03/programming.gif?fit=1281%2C716&ssl=1" min-width="200px" max-width="200px" width="400px" align="right" alt="Computer">

<p align="center">
    <img src="https://discord.c99.nl/widget/theme-3/914577400845721700.png" />
</p>

<p align="center">
    <img src="https://img.shields.io/github/followers/zSpl1nterUS?label=Follow&style=social" alt="github followers" /><br>
    <br>
    <img src="https://github-readme-stats.vercel.app/api?username=Cafeiinado&show_icons=true&theme=dark" alt="Ícaro" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cafeiinado&theme=dark" alt="Ícaro" />
   
</p>
<hr>

```js

const Discord = require("discord.js");
const { MessageButton, MessageActionRow } = require("discord.js");

module.exports = {
name: "sobre-mim",
run: async(client, message, args) => {

let idade = args.join("18");
let name = args.join("Ícaro");
    
let icaro = new Discord.MessageEmbed()
.setTitle("Desenvolvedor ${name}")
.setDescription("Olá! Meu nome é ${name}, e eu possuo ${idade} anos de idade.")
.setColor("RANDOM");
    
let trow = new Discord.MessageButton()
.setLabel("Desenvolvedor")
.setEmoji("☁")
.setStyle("LINK")
.setURL("https://github.com/Cafeiinado")
    
    
return message.reply({ embeds: [icaro], buttons: [trow] })
 }   
}
```

### 📋 Linguagens que utiliz em meus projetos.

<code><img height="30" src="https://img.shields.io/badge/PHP-blue?style=for-the-badge&logo=php&logoColor=white"></code>
<code><img height="30" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></code>


### 🚀 Programas que utilizo em meus projetos.

<code><img height="30" src="https://img.shields.io/badge/IntelliJ-black?style=for-the-badge&logo=intellij-idea&logoColor=white"></code>
<code><img height="30" src="https://img.shields.io/badge/VSCode-008B8B?style=for-the-badge&logo=visual-studio-code&logoColor=white"></code>
  
![Snake animation](https://github.com/NailsonDev/NailsonDev/blob/output/github-contribution-grid-snake.svg)

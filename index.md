# HTML

*Hypertext*
*Markup*
- Tag e elas sempre começa e terminar com
o sinal menor e maior < >.
- Atributos
*Language*

# CSS
Cascading StyleSheet
```css 
/* declarações */
body {
  background-color: #121214;
  color: white;
}
```

# JavaScript
```js
//variaveis
const mensagem = `Oi, tudo bem?`

// tipos de dados
  //number
  //string

//funcão
alert(mensagem)

//objeto javascript
//isso é uma estrutura de dados inicio
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gamil.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}
//isso é uma estrutura de dados fim

// [] isso significa array
let participantes = [
  {
    nome: "Mayk Brito",
    email: "mayk@gamil.com",
    dataInscricao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  }
]

//estrutura de repetição - loop inicio
  //para (cada participante de participantes)
  for(let participante of participantes) {
    //faça alguma coisa
    output = output + criarNovoParticipante(participante)
  //estrutura de repetição - loop fim
  }
```
# HTML

*Hypertext*
*Markup*
*Language*

- Tag marcações de linguagem
- tags podem ter atributos
width="100%" esse atributo colocado na tabela deixou os th separados, antes estavam todos juntinhos

tbody corpo da tabela

table tabela
thead cabeçalho
tr linhas
th nome
td informações nas partes da tabela

strong negrito

br quebra de linha

form serve para agrupar ideias de formularios
fieldset é conjunto de campos field = conjuntos set = campos
legend para textos

div só serve para agrupar outras tags, ela não tem significado
input cria um campo de texto, para escrever
placeholder dentro do input coloca algo escrito em cinza para a pessa escrever no input, como nesse caso Nome Completo
button = botão

onSubmit 
on = prestar atenção
submit = envio

header = cabeçalho

input wrapper = envolvendo um input


# CSS

```CSS
/*declarações*/
body {
  background-color: #121214;
  color: #ffffff;
}
```


#JavaScript
'''JavaScript// variaveis guardar uma informação para usar mais tarde
const mensagem = "Oi, tudo bem?"
//tipos de dados
  //number
  // string

// função
alert(mensagem)

// objeto javascript, tem propriedade e valor
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

//const não muda valor, let muda
//array []
let participantes = [
  {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
  }
]

// estrutura de repetição - loop
  for(let participante of participantes) {
    // faça alguma coisa aqui
    // enquanto tiver pessoas nessa lista
    output = output + criarNovoParticipante(participante)
  }

  const variavel = (função) => {
    argumento
  }

  event.preventDefault()
  ao clicar o botao o onsubmit quer colocar o evento para dentro
  mas o preventdefault não deixa esse botao fazer o padrão dele
  prevent = não faça o padrão
  default = padrão

  required = obrigatório

  ...espalhar, colocando todas as outras informações que já estavao lá


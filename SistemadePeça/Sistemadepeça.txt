// Função: Sistemadecadastramentodepeça (Peça, peso, quantidade, caracteres)
// cadastra uma nova peça  ( nome, peso, quantidade)
// - Nome da peça a ser cadastrada no sistema ( ex: Peça1, Chave)
// - Peso da peça a ser cadastrada no sistema ( ex: 100 g)
// - Quantidade da peça que esta sendo cadastrada ( ex: 01)
//----------------------------------------------------------------------------------------
// Váriveis
 let peso = 101;
 let listapeca = ["Peca1", "chave", "A", "Pneu", "motor"];
 // condicionais
  if (peso > 100){
      console.log("cadastrado efetuado com sucesso!");
  }
if (listapeca.length > 10){
 console.log("Limite atingide!")
}else{
console.log("Disponivel para cadastro")
}
// caracteres: laços de repetição
for(let index = 0; index < listapeca.length; index++){
    const pecaAtual = listapeca[index];
    if(pecaAtual.length<3){
    console.log(pecaAtual+ ": A peça possui menos que 3 caracteres")
    }else{
    console.log(pecaAtual + ": A peça pode ser cadastra")
    }

}
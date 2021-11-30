// sitema de contagem e classificação
//variavel
const quantiadeDeAluno = ["raynara", " larissa", "Bea", "Sandrine", "Rayla"]

for(let i=0; i < quantiadeDeAluno.length; i++){
    const qtde = i;
    const nome =quantiadeDeAluno[i]
    if(qtde % 2 == 0){
        console.log ("Par: "+qtde);
        console.log ("O nome do aluno"+ nome)

        if ( qtde == 0){
            console.log ("Zero: "+qtde);
        
        }

    }

    else if(qtde %2 !== 0){
        console.log("impar: "+qtde)
        console.log (" O nome do aluno " + nome)

    }

}
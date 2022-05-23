let lines = gets().split("\n");
let frase = " ";

let N = parseInt(lines.shift());

for ( let i = 0; i < N; i++ ) {

  if (i === N-1 ) frase += "Ho"  ;

  else frase +=  "Ho "   ;

}



print(frase + "!");
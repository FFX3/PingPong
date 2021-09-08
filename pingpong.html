<div id="PingPongOutput"></div>

<script>
function estCeChiffreDivisibleParN(chiffre, n){
  if(n === 0){
    console.log('On ne peux pas diviser par ZERO')
    return false
  }
  if(chiffre % n === 0){
    return true
  }
  return false
}

class Règle {
  constructor(divisiblePar, remplacement) {
    this.divisiblePar = divisiblePar
    this.remplacement = remplacement
  }

  testerLaRègle(chiffre){
    return estCeChiffreDivisibleParN(chiffre, this.divisiblePar)
  }
}

function retourneLesRésultasDesRègles(listeDeRègles, item){
  return listeDeRègles.map((règle)=>{
    if(règle.testerLaRègle(item)){
      return règle.remplacement
    }
    return undefined
  })
}

function modifierTextÀConditionDesRésultasDesRègles(original, résultasDesRègles){
  let nouveauText = original

  for(let i = 0; i < résultasDesRègles.length; i++){
    if(résultasDesRègles[i] !== undefined){
      if(nouveauText === original){
        nouveauText = résultasDesRègles[i]
      }
      else{
        nouveauText += résultasDesRègles[i]
      }
    }
  }

  return nouveauText
}


function retourneLeRésultaHTMLPingPong(début, fin, listeDeRègles){
  let htmlString = ''

  for(let i = début; i <= fin; i++){
    htmlString += `<p>${modifierTextÀConditionDesRésultasDesRègles(i, retourneLesRésultasDesRègles(listeDeRègles, i))} </p>`
  }

  return htmlString
}

//-----------------------------------------------------------------------------------------------

//Paramètre

let début = 1
let fin = 100

let listeDeRègles = [
  new Règle(3, 'Ping'),
  new Règle(5, 'Pong'),
]

//exemple d'autre paramètre possible

// let début = 1
// let fin = 105

// let listeDeRègles = [
//   new Règle(3, 'Zip'),
//   new Règle(5, 'Zap'),
//   new Règle(7, 'Zop')
// ]

//-----------------------------------------------------------------------------------------------

document.getElementById("PingPongOutput").innerHTML = retourneLeRésultaHTMLPingPong(début, fin, listeDeRègles)

</script>
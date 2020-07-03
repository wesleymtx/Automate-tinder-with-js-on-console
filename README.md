# Automate-tinder-with-js-on-console
Automate tinder with js on console

const automate = ()=>{
    let numero = Math.random()*10
    if(numero>5)
        like = document.querySelector('[aria-label="Gosto"]').click()
    else
    deslike = document.querySelector('[aria-label=Não]').click()
}
setInterval(automate,5000)

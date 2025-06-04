# ANTON NILOV

## CONTACTS
**Address:** 72/17 Viktor Kupradze St, Tbilisi 0163\
**Phone:** +995 555 50 32 49\
**E-mail:** ale.amans.an@gmail.com\
**GitHub:** [AleAmans](https://github.com/AleAmans)\
**Discord** [@ale_amans](https://discordapp.com/users/952332536112103534)\
**Telegram** [@Amantes_Cor](https://t.me/Amantes_Cor)
## ABOUT ME

## SKILLS
- HTML
- CSS
- JavaScript (elementary)
- Git
- VS Code
- Adobe Photoshop, Adobe Lightroom, CorelDRAW
## CODE
One-button idea generator for procrastination:
```
function getRandomElement(arr) {
  let randIndex = Math.floor(Math.random() * arr.length);
  return arr[randIndex];
}

let button = document.querySelector('.button');
let phrase = document.querySelector('.phrase');
let advice = document.querySelector('.advice');
let image = document.querySelector('.image');

button.addEventListener('click', function () {
  let randomElement = getRandomElement(phrases);
  smoothly(phrase, 'textContent', randomElement.text);
  smoothly(image, 'src', randomElement.image);

  if (randomElement.text.length > 40) {
    advice.style.fontSize = '33px';
  } else {
    advice.style.fontSize = '42px';
  }
});

for (let i = 0; i <= 2; i = i + 1) {
  smoothly(phrase, 'textContent', phrases[i].text);
  smoothly(image, 'src', phrases[i].image);
}
```
## EXPERIENCE

## EDUCATION
**College of Automation and Radio Electronics No. 27** - specialty *electrician*\
**RS School** - course *"JavaScript/Front-end. Stage 0"* (in progress)
## LANGUAGES
**Russian** - native speaker\
**English** - A2\
**Spanish** - entry level (half a year of living in Mexico)
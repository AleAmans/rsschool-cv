# ANTON NILOV
![my photo](/rsschool-cv/images/CV-DSC06974.jpg)
---
## CONTACTS
**Address:** 72/17 Viktor Kupradze St, Tbilisi 0163\
**Phone:** +995 555 50 32 49\
**E-mail:** ale.amans.an@gmail.com\
**GitHub:** [AleAmans](https://github.com/AleAmans)\
**Discord** [@AleAmans](https://discordapp.com/users/952332536112103534)\
**Telegram** [@Amantes_Cor](https://t.me/Amantes_Cor)
## ABOUT ME
I am 34 years old. I was born and raised in Moscow, but now I live in Tbilisi. I love my wife, music, coffee and Guinness 😎\
I've wanted to try learning programming for a long time, but there was always a "friend" who talked me out of it. Now I realize that I've wasted a lot of time, because I'm very interested in coding - it's like playing a computer game. I like learning and learning new things. I'm a perfectionist, and it's important to me that my code not only works well, but also looks beautiful. My calm nature allows me to perfectly fit into teamwork. I love it when my work is beneficial.
## SKILLS
- HTML
- CSS
- JavaScript (elementary)
- Git
- VS Code
- Adobe Photoshop, Adobe Lightroom, CorelDRAW
## CODE
One-button idea generator for procrastination:\
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
## EXPERIENCE
I learned the basics of Front-end development based on Yandex Practicum.\
HTML and CSS were studied by writing the code for the [«4 правила вёрстки»](https://sandbox.practicum-team.ru/tasks/000-freetrack/04-more-css/17-one-step/example-02/pre/) landing page.\
JavaScript was studied by writing code for a website about [procrastination](https://code.s3.yandex.net/web-developer/procrastinate/index.html).
## EDUCATION
**College of Automation and Radio Electronics No. 27** - specialty *electrician*\
**RS School** - course *"JavaScript/Front-end. Stage 0"* (in progress)
## LANGUAGES
**Russian** - native speaker\
**English** - A2\
**Spanish** - entry level (half a year of living in Mexico)
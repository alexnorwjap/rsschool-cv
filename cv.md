# Aleksandr Denisov 


## Contact Info

 - Address: Saint Petersburg, Russia
 - Telegram: [@telegram](https://t.me/)
 - E-mail: alex.norw.jap@gmail.com
 - LinkedIn: soon
 - GitHub: [@GitHub](https://github.com/alexnorwjap)

## About

>**Don’t be just a programmer, be a problem solver.**

- I am interested in programming, because I saw so many amazing things that can be built with it.
That's why I think that it's not enough to just programm, the main puprose should be to build something that matters, something that solves problems.
- I want to become a problem-solver, creator, innovator — not just a programmer. Programming is simply a tool to build amazing things.
- I want to help to create something meaningful, to help real people with the real problems.


## Skills
- HTML(Intermediate)
- CSS/SASS (Intermediate)
- JavaScript (Basic-Intermediate)
- Vue (Basic)
- Git (Basic)
- Bundler: Vite(Basic)
- Figma(Basic)


## Code examples:
>The base for the modal window, basic settings and closing conditions that will follow all child classes for individual buttons.

```javascript
class BaseModal {
  constructor() {
    this.modal = document.querySelector('#modal');
    this.modalWindow = document.querySelector('#modal-window');
    this.btnClose = document.querySelector('#btn-close');
    this.titleModal = document.querySelector('#modal-title');
    this.textModal = document.querySelector('#modal-text');
    this.imageModal = document.querySelector('#image-modal');
  }
  
  initEvents() {
    this.modal.addEventListener('click', this);
    this.btnClose.addEventListener('click', this);
  }

  handleEvent(event) {
    if (this.isCLoseAction(event)) {
      return this.closeModalWindow();
    }
  }

  isCLoseAction(event) {
    return event.target === this.btnClose || event.target === this.modal;
  }

  openModalWindow() {
    this.modal.classList.add('active');
    this.modal.querySelector('.modal__window').classList.add('active');
    document.querySelector('body').classList.add('lock');
  }

  closeModalWindow() {
    this.modal.classList.remove('active');
    this.modal.querySelector('.modal__window').classList.remove('active');
    document.querySelector('body').classList.remove('lock');
  }
}
```


## Education(Self Education):

##### HTML/CSS(SASS)/JS(base)
- youtube lessons
- https://www.cssportal.com/
- https://www.w3schools.com/

#### Git/Figma/ Vite
- documentation
- youtube lessons

#### JavaScript
- youtube lessons
- https://developer.mozilla.org/ru/
- https://learn.javascript.ru/

#### Vue
- https://vuejs.org/


## Experience

- soon
- [this](https://alexnorwjap.github.io/rsschool-cv/)

###	Languages

-	Engllish A2

##	[![RSS](img/logo.png)](https://alexnorwjap.github.io/rsschool-cv/cv)
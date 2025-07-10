# Aleksandr Denisov 


## Contact Info

 - Address: Saint Petersburg, Russia
 - Telegram: [@telegram](https://t.me/Norw_Jap_Can)
 - E-mail: alex.norw.jap@gmail.com
 - LinkedIn: soon
 - GitHub: [@GitHub](https://github.com/alexnorwjap)

## About

- I’m interested in programming because I’ve seen how many incredible things can be built with it.
To me, it’s not just about writing code — it’s about creating something meaningful that solves real problems.
- I aim to be an innovative creator who focuses on solving real-world challenges. Programming is a powerful tool for bringing valuable ideas to life.

## Tech Stack
- HTML
- CSS/SASS
- JavaScript
- Vue
- Git
- Bundler: Vite
- Figma

## Code examples:

```javascript
export class AnimateCounter {
  constructor(target, endValue, duration) {
    this.startTime = performance.now();
    this.counterElement = target;
    this.endValue = endValue;
    this.duration = duration;
    this.startAnimation();
  }

  formatNumber(value) {
    if (value >= 10000) {
      const kValue = Math.floor(value / 1000);
      const remainder = value % 10000;
      return `${kValue}k${remainder > 0 ? '+' : ''}`;
    }
    return value;
  }

  update(currentTime) {
    const progress = Math.min((currentTime - this.startTime) / this.duration, 1);
    const currentValue = this.formatNumber(Math.floor(this.endValue * progress));

    this.counterElement.textContent = currentValue;
    if (progress < 1) {
      requestAnimationFrame((time) => this.update(time));
    }
  }

  startAnimation() {
    requestAnimationFrame((time) => this.update(time));
  }
}
```

[Nifter](https://github.com/alexnorwjap/Nifter/tree/main/src/assets/js)

- Utilization of OOP principles and separation of functionality into classes (DropdownManager, SellerSlider, DataLoader, PageSearch)
- Exporting functions and classes for use in other modules
- Encapsulation of logic within classes
- Asynchronous functions (async/await)
- Working with Promise for parallel data loading
- Arrow functions
- Destructuring assignment
- Using try/catch blocks for error handling in asynchronous operations
- Logging error messages to the console
- Providing user-friendly error feedback
- Implementation of drag functionality in slider with corresponding visual indicators (cursor changes)
- Dropdown menu with outside click handling
- Highlighting search text in results
- Responsive slider adjustments for different screen sizes
- Dynamic calculation of element dimensions

## Education(Self Education):

##### HTML/CSS(SASS)/JS(base)
- https://www.cssportal.com/
- https://www.w3schools.com/
- youtube lessons

#### JavaScript
- youtube lessons
- https://developer.mozilla.org/ru/
- https://learn.javascript.ru/

#### Vue
- https://vuejs.org/

#### Git / Figma / Vite
- documentation
- youtube lessons


## Experience

- [Nifter(JS)](https://alexnorwjap.github.io/Nifter)

###	Languages

-	Engllish A2


>**Don’t be just a programmer, be a problem solver.**

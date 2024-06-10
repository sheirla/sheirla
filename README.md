```js
class Probabilities {
    constructor() {
        this.alias  = [ 'Probabilities', 'Socket' ]
    }

    contact() {
        const discord  = '@wa6iman'
        return discord
    }

    life() {
        const age        = 27
        const occupation = 'Freelance Software Developer'
        const hobbies    = [ 'Programming', 'Reverse Engineering', 'Reading' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'Javascript', 'Python', 'C#', 'C++', 'PHP' ];
        const learning          = 'Golang';
        const ide               = ['Visual Studio Code','NeoVim'];

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

export default Probabilities
```

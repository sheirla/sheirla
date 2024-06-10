class Probabilities {
    constructor() {
        this.alias  = [ 'Probabilities', 'Socket' ]
    }

    contact() {
        const discord  = '@shareholders'
        const telegram = 't.me/gaveaway'
        const email    = 'xmlrequest@proton.me'
        
        return discord, telegram, email
    }

    life() {
        const age        = 19
        const occupation = 'Freelance Software Developer'
        const hobbies    = [ 'Programming', 'Reverse Engineering', 'Reading' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'Javascript (Node.js Framework)', 'Python', 'C#' ];
        const learning          = 'Golang';
        const ide               = 'Visual Studio Code';

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

export default Probabilities

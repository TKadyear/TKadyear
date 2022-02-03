```javascript
class Me {
    constructor(){
        firstname = "Tamara",
        surname = "Kadyear Saber",
        age = 25,
        pronouns = "she/her"
    }
}
class About extends Me {
    getCurrentStudies() {
        return "Course of Programming and Front End Web Development (403 hours)";
    }
    getPersonalChallenges() {
        return "30 days with Vue.js";
    }
    getSpokenLanguages(){
        return ["Spanish", "Arabic" , "English"];
    }
    getDailyKnowledge(){
        return ["HTML5", "CSS3", "Javascript", "Vue.js", "Tailwind Css", "Vite", "Figma"];
    }
    getFutureGoal() {
        return "To contribute to open source";
    }
    getContact(){
        const Linkedin = "tamara-kadyear-saber";
        return Linkedin
    }
}
About.getContact()
```
[LinkedIn](https://www.linkedin.com/in/tamara-kadyear-saber/)

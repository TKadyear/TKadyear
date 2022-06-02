```javascript
class Me {
    constructor(){
        firstname = "Tamara",
        surname = "Kadyear Saber",
        age = 26,
        pronouns = "she/her"
    }
}
class About extends Me {
    getCurrentStudies() {
        return "Training FullStack MERN React";
    }
    getPersonalChallenges() {
        return "Learn about Test Driven Development";
    }
    getSpokenLanguages(){
        return ["Spanish", "Arabic" , "English"];
    }
    getDailyKnowledge(){
        return ["HTML5", "CSS3", "Javascript", "Vue.js","VueX" ,"React", "Redux" ,"Tailwind Css", "Vite", "Figma"];
    }
    getFutureGoal() {
        return "To contribute to be Full Stack Developer";
    }
    getContact(){
        const Linkedin = "tamara-kadyear-saber";
        return Linkedin
    }
}
About.getContact()
```
[LinkedIn](https://www.linkedin.com/in/tamara-kadyear-saber/)

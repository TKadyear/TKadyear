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
        return "Learning  about the Azure AZ-204 Developing Solutions for Microsoft Azure certification exam topics.";
    }
    getPersonalChallenges() {
        return "Azure 30 Days Challenge";
    }
    getSpokenLanguages(){
        return ["Spanish", "Arabic" , "English"];
    }
    getDailyKnowledge(){
        return ["HTML5", "CSS3", "Javascript", "Angular","Fastify", "Docker", "Bicep", "Typescript", "Kubernetes"];
    }
    getContact(){
        const Linkedin = "tamara-kadyear-saber";
        return Linkedin
    }
}
About.getContact()
```
[LinkedIn](https://www.linkedin.com/in/tamara-kadyear-saber/)

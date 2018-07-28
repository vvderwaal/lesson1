function myFirstApp(name, age) {
 
    alert("Привет! Меня зовут " + name +  ", и это моя первая программа!");
 
 function showSkills(){
        let skills = ["html", "css", "JavaScript"];
        document.write("Я владею: " + "<br>");
        for(let i = 0; i < skills.length; i++){
            document.write(skills[i] + "<br>");
        }

    }
 
    showSkills();
    
    function checkAge() {
        if (age > 18) {
            alert("Добро пожаловать на сайт!");
        } else {
            alert("Извините, доступ ограничен!");
        }
    }
    function calcPow(num) {
        alert(num * num);
    }
    calcPow(5);
}
 
myFirstApp("Касапиди", 23)

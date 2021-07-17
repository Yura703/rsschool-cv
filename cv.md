# Yury Lapitski
## Contacts
* __Tel:__ +375(29) 703-80-52;
* __E-mail:__ lyurik@tut.by;
* __Discord:__ yura#3119;
* __Telegram:__ yura703.
## About
I love programming and try to constantly develop in this. I want to become a Full-stack development specialist.
In my free time I am engaged in self-study using various online courses (coursera.org, itvdn.com and others), I train on codewars.com and nodeschool.io.
## Skills
Basic knowledge of C#, WPF, ASP .Net Core (MVC), HTML, CSS, JavaScript, NodeJs, SQL, Entity Framework, Git, Microsoft SQL Server, UML
## Code sample (codewars task)
    function startTest() {
        document.querySelectorAll("button").forEach(elem => {
            elem.disabled = true;
        });;
        for (let i = 0; i < tests.length; i++) {
            let div = document.createElement("div");
            let title = "<strong>" + tests[i].quest + "</strong>";
            div.innerHTML = title;
            document.body.append(div);
            for (let j = 0; j < 4; j++) {
                let checkBox = document.createElement("input");
                checkBox.type = "checkbox";
                let label = document.createElement("label");
                label.textContent = tests[i].answer[j];
                let br = document.createElement("br");
                document.body.append(checkBox, label, br);
            }
        }
        let button = document.createElement("button");
        button.textContent = "Отправить";
        button.addEventListener("click", function () {
            CheckTest();
        });
        document.body.append(button);
    } 
## Work experience
2016-now time - Beltelecom, engineer (non-IT sphere).
## Education
* Institute of Information Technologies BSUIR (2019-2021), software engineer;
* Belarusian National Technical University (2000-2006), electrical engineer.
## English level
A2. I improve the level of English at a language school.
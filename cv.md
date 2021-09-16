# Tukpetov Raiymbet Zhumanoruly
## Junior Fullstack Developer

### Contacts:

**Location:** Taraz, Kazakhstan\
**Phone:** +7 707 540-02-13\
**Email:** tukpetov94.sdu@gmail.com, tukpetov@bk.ru\
**Discord:** Raiymbet#6496\
**Skype:** live:tukpetov

### 1. About me:
I can say about myself that by the type of character I am mostly an introvert, by the type of temperament I am phlegmatic and melancholic. I am ENFJ-A personality. I like to learn something new and always try to improve my knowledge. Concerning the large size of work, I am lazy and thinking about how to shorten or automate the process to work as less time. In my free time I read fiction or professional literature. Sometimes I drawing or writing as a hobby. I am a member of the Run Decathlon running club and try not to miss marathons.

I look at my professions as a hobby. I believe that Computer Science improves the efficiency of work and life of people. Like everyone else, I have many goals and aspirations, as for the professions I strive to improve the quality and efficency of knowledge of Computer Science in Kazakhstan.

Regarding plans for the future, I plan to enroll PhD program in Data Science and Machine Learning, as well to join the EPAM Kazakhstan team.

### 2. Skills:
* HTML5, CSS3, SCSS, LESS
* JavaScript, JQuery, Ajax, hichart.js, amchart.js, 3d.js
* Angular, Rx.js, Typescript
* Git (CI/CD)
* OOP, Design Patterns, MVC, Asynchronous programming, Subscription, Promise, BPM
* Python (Advanced, Conda, Numpy, Pandas, scikit-learn, opencv, tenserflow, keras), Java(Advanced, ORM, Spring Framework, Hibernate), PHP (Advanced), Android (Basic)
* SQL, MySQL, MS Sql, Oracle
* UML
* CRM (ModX Re, DamuCRM)
* CISCO Routing and Switching
* Editors: VS Code, PyCharm, Jupyter

### Code example:
Binary search tree validation from CODEWARS:
```javascript
const isBST = node => {
    // Give the array of tree.
    let tree_arr = _isBST(node),
        asc = tree_arr[0] < tree_arr[1],
        result = true;
    
    for (let i = 0; i < tree_arr.length - 1; i++) {
        if (asc) {
            if (tree_arr[i] > tree_arr[i+1]) {
                result = false;
                break;
            }
        } else {
            if (tree_arr[i] < tree_arr[i+1]) {
                result = false;
                break;
            }
        }
    }
    
    return result;
};

const _isBST = node => {
    if (!node) {
        return [];
    }
    
    let left_arr = [], right_arr = [];
    
    if (node.left) {
        left_arr = _isBST(node.left);
    }
    
    if (node.right) {
        right_arr = _isBST(node.right);
    }
    
    return left_arr.concat([node.value]).concat(right_arr);
}
```

### 3. Experience: 
* I started my career since 09.2015 to 07.2016 at the university from the position - IT Support at SDU, Almaty. My responibilities included maintaining of computers and networks at university. Also was redesigned the website https://infomatrix.asia, developed on the framework codeigniter v2.0. I was added and fixed functionalities like: registration, authorithation, team registration, evaluation team projects, viewing the results... 
Also I was developed the information portal aqparat.kz for faculty of journalists, used framework Laravel v4.2. Briefly about the functionality, in portal has published news articles by journalists, with the ability to administer by moderators. Source code: https://github.com/Raiymbet/aqparat.kz
Also was developed project by team for rapid online testing like Kahoot. Used technologies JavaScript, PHP and MySQL. Source code: https://github.com/Raiymbet/gamification-sdu-en3-04

* RaarLabs, Full Stack Developer, since 02.2018 - 08.2018.
There were developed online stores on CMS MODxRe with functionalities publishing by moderators and ordering by clients. almatuning.kz - online store for car tuning. almatexltd.kz - online store of socks. astana-spk.kz - information website. Landing page for passacademy of language school, source code: https://github.com/Raiymbet/passacademy
Used technologies: MySQL, JavaScript, JQuery, Ajax, HTML, CSS, PHP.

* IDET, Frontend Developer, since 09.2018 - 12.2020.
Worked on team and projects such as: gpn.idet.kz, portalbd.kz, portalmio.kz, admin.portalbd.kz - information and analytical portal. Used technologies: Angular from v4 to 12 (Modules, Model biding, Reactive Form, Gridster, 3d.js, Drawing SVG, Creating libraries), .NET, MS SQL (I don't have privilegies for publish source code).
Was developed frontend for face recognition, car number recognition with real-time. Source code: https://bitbucket.org/rtukpetov/facerecognition/src/master/, https://bitbucket.org/rtukpetov/numberrecognition/src/master/

* TOO DevArt, Full Stack Developer, since 12.2020 - 07.2021
There were modular developed of business process automation functionality. Was developed the portal for workflow and process analytics - https://devportal.ekpd.kz. Used technologies: DamuCRM, BPM Camunda, Lua script, HTML, CSS, angular.js, amchart.js (I don't have privilegies for publish source code).

### 4. Education: 
* Bachelor, university of Suleiman Demirel(SDU), Kazakhstan, Almaty.
    * Computer Science and Software
* Master, Satbayev University(SU), Kazakhstan, Almaty.
    * Data Science and Machine Learning

### 5. Knowledge of Languages:
* Kazakh language - the native language
* Russian language - advanced, read various professional books and fiction, speak freely
* English language - preintermediate
* Turkish language - basic
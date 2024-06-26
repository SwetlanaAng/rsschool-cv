###### rsschool-cv
---
# Svetlana Angeliuk
---
### Contacts
---
* **location:** Budapest, Hungary
* **Phone:** +36 20 452 1001
* **Email:** angeliuksvetlana128@gmail.com
* **GitHub:** [SwetlanaAng](https://github.com/SwetlanaAng)
* **Telegram:** [@SvetlanaAngely](https://web.telegram.org/k/#@SAngeliuk)
* **Discord:** swetlanaang_00593_88551

### About myself
---
I can be a hardworking, curious and comfortable employee. I have excellent soft skills! I can become a wonderful part of a team and be relied upon and trusted to complete important tasks. I can and love to learn. Disciplined.
A few years ago I decided to try myself in something new for me and promising, so I tried front-end development. I've hit the mark and feel the strength to develop in this direction,reach the goal to become a real professional

### Skills
---
- HTML
- CSS (SASS/SCSS, Bootstrap, Flexbox)
- JavaScript (Fundamentals, ES6+, DOM, JSON, Asynchronous JavaScript. Webpack)
- React (basics)
- Gulp
- Git/GitHub
- Avocode, Figma

### Code examples
---
```
function formMap(set1, set2, set3, map) {
    map = runThroughSet(set1, map);
    map = runThroughSet(set2, map);
    map = runThroughSet(set3, map);
    return map;
}

function runThroughSet(set, map) {
    for (let el of set) {
        if (map.has(el)) {
            map.set(el, map.get(el)+1)
        } else {
            map.set(el, 1)
        }
    }
    return map;
}

function formAnswer(map) {
    let arr = [];
    for (let el of map) {
        if (el[1] >= 2) {
            arr.push(el[0]);
        }
    }
    arr.sort((a,b)=>a-b);
    
    return arr;
}

    
function main() {


    let n1 = +readline(); //function that accept the data from the task
    let arr1 = readline().split(' ');
    let set1 = new Set(arr1);
    let n2 = +readline();
    let arr2 = readline().split(' ');
    let set2 = new Set(arr2);
    let n3 = +readline();
    let arr3 = readline().split(' ');
    let set3 = new Set(arr3);
    let myMap = new Map();
    myMap = formMap(set1, set2, set3, myMap)

    
    print(formAnswer(myMap).join(' ')); 
    return 0;    
}
```

### Work expirience
--- 
took part in writing several projects

- a small diploma application on mvc architecture to reduce url-adresses for registered users (https://github.com/SwetlanaAng/diplom-project)
- an educational project on JavaScript (https://github.com/SwetlanaAng/food)

### Education
--- 
1. Professional retraining at the Russian Economic University named after G.V. Plekhanov under the program "Front-end development and web design"
2. Programming online school "It-proger" full-stack programmer
3. UDEMI "web-developer" and "JavaScript and React" in process

### Languages
---
* Russian - native speaker
* English - B2

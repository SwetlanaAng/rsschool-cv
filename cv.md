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
- VS Code
- Git/GitHub
- Avocode, Figma

### Code examples
---
```
The task: Given an integer array nums, return all the triplets [nums[i], nums[j], nums[k]] 
such that i != j, i != k, and j != k, and nums[i] + nums[j] + nums[k] == 0.
The solution:
let threeSum = function(nums) {
    let res = new Set();
    nums.sort((a,b)=>a-b)
    for(let i = 0; i<nums.length-2; i++){
        let l = i+1;
        let h = nums.length-1;
        if (i > 0 && nums[i] === nums[i - 1]) continue;
        
        while(l<h && nums[i]<=0){
            
            let sum = nums[i] + nums[l] + nums[h];
            if(sum>0){
               h--;
           }
           else if(sum<0){
               l++
           } else if (sum ==0 && l!=h){
                res.add([nums[i], nums[l], nums[h]]);
                
                l++;
                h--;
                while (nums[l] == nums[l - 1]) l++;
                while (nums[h] == nums[h + 1]) h--;
           }  
        } 
    }res = Array.from(res); 
       return res
};

```

### Work experience
--- 
I've taken part in writing several projects

- a small diploma application on mvc architecture to reduce url-addresses for registered users (https://github.com/SwetlanaAng/diplom-project)
- an educational project on JavaScript (https://github.com/SwetlanaAng/food)

### Education
--- 
1. Professional retraining at the Russian Economic University named after G.V. Plekhanov under the program "Front-end development and web design"
2. Programming online school "It-proger" full-stack programmer
3. UDEMI "web-developer" and "JavaScript and React" in process
4. RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

### Languages
---
* Russian - native speaker
* English - B2
! [certificate photo](/Users/svetlanaangeliuk/Desktop/Screenshot.png)

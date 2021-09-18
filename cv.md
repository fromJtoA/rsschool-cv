# **Michael Nefyodov**
### **Contact information:** 

**Telepfone:** 89276906121 

**E-mail:** mixan.rus@gmail.com 

**Telegram:** justIsJ
### **About Myself:**
I have different working experience. For example I can organize sporting event for 100 people or make a plan of setting airplane`s antenna. I am an engineer now. Web coding is very interesting sphere for me, because I want to have actual profession and to be useful for community.
### **Skills:**
* JavaScript basic
* HTML5, CSS3 basic
* Git, Github basic
* QA basic
### **Code example:**
**Task:**
Your task is to write such a run-length encoding. For a given string, return a list (or array) of pairs (or arrays) [ (i1, s1), (i2, s2), …, (in, sn) ], such that one can reconstruct the original string by replicating the character sx ix times and concatening all those strings. Your run-length encoding should be minimal, ie. for all i the values si and si+1 should differ.
```  
  var runLengthEncoding = function(str){

  console.log(str);
  
  let arr = str.split('')
  
  arr.push(true);
  
  let count = 1;
   
  let res = [];
  
  console.log(arr);
  
  for (let i = 0; i < arr.length - 1; i++) {
  
  if (arr[i] === arr[i + 1]) {
    
  count ++;
      
  } else {
    
  res.push([count, arr[i]]);
      
  count = 1;
      
  }
    
  }
  
  return res;
  
  } 
  ```
  ### **Education:**
[Samara National Research University](https://ssau.ru/english)

RS School «JavaScript/Front-end. Stage 1» (in progress)
### **English:**
**B1**

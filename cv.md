# Alexandr Sadikov

### Contact Info

e-mail: sav1982@inbox.ru

mobile phone: +7(908)729-13-32

### Summary

I want to learn more about how best to use HTML, CSS and JavaScript when developing Web applications, learn new features from professionals and as a result write stable, well-supported applications. I hope that this internship will help me better understand the nuances of JavaScript, ReactJS and will help me answer many of the questions that arise in my self-learning activities!

### Skills

C(entry level), Java(entry level), Python(entry level), JavaScript(entry level), ReactJS(entry level), JQuery(entry level), HTML, CSS

### Code examples

```javascript
    function arrayToList(arr){
    let list = null;
    for(let i = arr.length-1; i>= 0; i--){
        list={
            value: arr[i],
            rest: list
        };
    }
    return list;
}

function listToArray(list){
    let arr = [];
    let lst = list.rest;;
    arr.push(list.value);
    while(lst.rest){
        arr.push(lst.value);
        lst = lst.rest;
    }
    arr.push(lst.value);
    return arr;
}
```
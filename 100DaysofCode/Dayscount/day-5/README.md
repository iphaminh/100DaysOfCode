question is 

// 1. Grab the save-el paragrah and store it in a variable called saveEl
let countEl = document.getElementById("count-el")
let count = 0

function increment() {
    count += 1
    countEl.innerText = count
}

function save() {
    // 2. Create a variable that contains both the count and the dash separator, i.e. "12 - "
    // 3. Render the variable in the saveEl using innerText
    // NB: Make sure to not delete the existing content of the paragraph
    console.log(count)
}


<!-- solution 1 -->

// 1. Grab the save-el paragrah and store it in a variable called saveEl
let saveEl = document.getElementById("save-el")
let countEl = document.getElementById("count-el")
let count = 0

function increment() {
    count += 1
    countEl.innerText = count
}

function save() {
    let sav = count + "-"
    saveEl.innerText = saveEl.innerText + sav 
    // 2. Create a variable that contains both the count and the dash separator, i.e. "12 - "
    // 3. Render the variable in the saveEl using innerText
    // NB: Make sure to not delete the existing content of the paragraph
    console.log(count)
}

<!-- solution 2 -->

// 1. Grab the save-el paragrah and store it in a variable called saveEl
// 1. Grab the save-el paragrah and store it in a variable called saveEl
let saveEl = document.getElementById("save-el")
let countEl = document.getElementById("count-el")
let countNew = 0
let prNew = ""

function increment() {
    countNew += 1
    countEl.innerText = countNew
}

function save() {
    prNew = "-"
    saveEl.innerText = saveEl.innerText + countNew + prNew
    // 2. Create a variable that contains both the count and the dash separator, i.e. "12 - "
    // 3. Render the variable in the saveEl using innerText
    // NB: Make sure to not delete the existing content of the paragraph
  
}
console.log("")


<!-- solution 3 -->

// 1. Grab the save-el paragrah and store it in a variable called saveEl
let saveEl = document.getElementById("save-el")
let countEl = document.getElementById("count-el")
// let countOld = 0
// let countNew = 0
// let prOld = ""
// let prNew = ""

// function increment() {
//     countOld = countNew
//     countNew = countOld + 1
//     countEl.innerText = countNew
// }

// function save() {
//     prNew = prOld + "-"
//     saveEl.innerText = saveEl.innerText + countNew + prNew
//     // 2. Create a variable that contains both the count and the dash separator, i.e. "12 - "
//     // 3. Render the variable in the saveEl using innerText
//     // NB: Make sure to not delete the existing content of the paragraph
  
// }


Note: so the Reason i dont know why it save the prvious string/ result because there are 2/3 different strings are add up. So when strings are combined they are stay close together not same as number

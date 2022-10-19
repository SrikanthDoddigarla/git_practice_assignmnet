# git_practice_assignmnet
let str="naman"
let cat="";
    for (let i=str.length-1;i>=0;i--){
        cat=cat+str[i];
    }
    if (cat!=str){
        console.log("Yes");
    }
    else {
        console.log("No")
    }
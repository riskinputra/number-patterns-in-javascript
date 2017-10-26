# Number Patterns Program in Javascript

#### Square
```
/*-------------one------------*/
let satu = ''
for(var i = 1; i <=5 ; i++){
  for(var j = 1; j <= 5; j++){
    satu +='1'
  }
  satu+='\n'
}

console.log(satu)

// OUTPUT
/*
  11111
  11111
  11111
  11111
  11111
*/

/*-----------two---------------*/
let satu = ''
for(var i = 1; i <=5 ; i++){
  for(var j = 1; j <= 5; j++){
    if(i%2 != 0){
      satu+='1'
    }else{
      satu+='0'
    }
  }
  satu+='\n'
}

console.log(satu)

// OUTPUT
/*
  11111
  00000
  11111
  00000
  11111
*/


/*-----------three------------*/
let satu = ''
for(var i = 1; i <=5 ; i++){
  for(var j = 1; j <= 5; j++){
    if(j%2 != 0){
      satu+='0'
    }else{
      satu+='1'
    }
  }
  satu+='\n'
}
console.log(satu)

// OUTPUT
/*
  010101
  010101
  010101
  010101
  010101
*/

/*------------four-------------*/
let satu = ''
for(var i = 1; i <=5 ; i++){
  for(var j = 1; j <= 5; j++){
    if(i == 1 || i == 5){
      satu+='1'
    }else{
      if(j == 1){
        satu+='1'
      }else if(j > 1 && j < 5){
        satu+='0'
      }else if( j == 5){
        satu +='1'
      }
    }
  }
  satu+='\n'
}

console.log(satu)
//OUTPUT
/*
  11111
  10001
  10001
  10001
  11111
*/

```

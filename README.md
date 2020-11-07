# Sprint 5



  ## Letter Count In A Given String
  This study aims to develop algoritm skills


  ## Descriptiom
  - Write code block that take string and letter(myFunction(myString, meyLetter)), and return the number of specific letter in the string.
  
  - For example => myFunction("clarusway", "a") Output => 2⚠  
  - Please write your own code block to improve your algorithm skills 
  <br> 

   ``` Check It```   ```➡```  [SampleProject]('https://code-code-team.github.io/SPRINT5--LETTER-IN-STRING/')
  
  <center>🔥 Happy Coding!🔥 </center>

  ---
  ### Sample Function in Js
  ---
  
  ```bash
  function findLetter(text, let){
    console.log(text,let)
    let count = 0
    for(let i = 0 ; i < text.length ; i++){
        if(text.toLowerCase()[i] == let.toLowerCase()){
            count++
        } 
    }
    const result = `${text} kelimesinde ${let} harfi ${count} kez geçmektedir.`
    return result

  ```

  ### In Python ```count() method ```

  ```bash
  string.count(letter)
   ```
  ```bash
  string = input('Enter A String  : ')
letter = input('Enter A Letter  : ')
count = string.lower().count(letter.lower())
print(f'{string} kelimesinin içerisinde {letter} kelimesi {count} defa geçmektedir')

  ```
  
  ---

# Node Ecosystem, TDD, CI/CD

[Home](/README.md) | [Back](/401-main/401TableofContents.md)

## Questions:

1. Describe (in plain English) Who Array.map() does
  - .map() is a method that creates a new array used with another function. The map method will take every element in that array and run the function through it and returning a new array not changing the original array

2. Describe (in plain English) Who Array.reduce() does
  - .reduce() returns the sum of the array

3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
- With normal Promise .then() syntax

        superagent.get('https://swapi.dev/api/people/2/')
          .then( data => {
          console.log({[data.body.name]: data.body.url} );
        })
          .catch ( err => console.log (err));

- Again with async / await syntax

        async function getCity(city) {
          try{
           let results = await superagent.get(`https://geocode.xyz/${city}?json=1`);
            console.log(results.body.latt, results.body.longt)
          } catch(err){
          console.log(err)
          }
  
        }       

4. Explain promises as though you were mentoring a Code 301 level student
  - A promise is kind of like an IOU. The code will continue to run while waiting for a response for the API. When the IOU or promise comes back, the function will be completed.


5. Are all callback functions considered to be Asynchronous? Why or Why Not?
 - not always but they can be used in an asynchronous manner

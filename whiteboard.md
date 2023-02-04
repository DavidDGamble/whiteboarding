// write an alg to check if strings are unique
// cant convert to array or use array methods
// input always a string no funny stuff
// input = "hello"
// output = false

// function unique
  // for loop over the string
  	// for loop over string
  		// if indexs do not match 
      	// if string[index1] === string[index2]
        	// return false
  // return true
  
const isUnique = (string) => {
  for (let i = 0; i < string.length; i++) {
    for (let x = 0; x < string.length; x++) {
      if (i !== x) {
        if (string[i] === string[x]) {
          return false;
        };
      };
    };
  };
  return true;
};
  
  
// function isUnique (string, unique = true)
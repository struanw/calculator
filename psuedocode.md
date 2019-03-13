Psuedocode for calulator


// need to store enteered values
// need to dispaly total

// all need to be buttons


// ****** NOT SURE WHAT THIS DOES ****************************

    var temp = '';
    $("button").on('click', function() {
 	    var val = $(this).text();

    // Got a number, add to temp
         if (!isNaN(val) || val === '.') {
          temp += val;
          $("#answer").val(temp.substring(0,10));

    
        // Got some symbol other than equals, add temp to our entries
        // then add our current symbol and clear temp
        } else if (val === 'AC') {
           entries = [];
           temp = '';
          total = 0;
          $("#answer").val('')

//*****************************************************



// Need a clear button fuction
if clicked display nothing/zero

  
// need multiply button fuction
//if 'x' button pressed
//multiply number (using *)

 // need division button fuction
//if '/' button pressed
//multiply number (using /)   
    
// need add button fuction
//if '+' button pressed
//multiply number (using +)

// need subtract button function
//if '-' button pressed
//multiply number (using -)


//Need equals button function
//if '=' pressed 
//display result


//Function to perform all the opreations


    var nt = Number(entries[0]);
    for (var i = 1; i < entries.length; i++) {
      var nextNum = Number(entries[i+1])
      var symbol = entries[i];
      
      if (symbol === '+') { nt += nextNum; } 
      else if (symbol === '-') { nt -= nextNum; } 
      else if (symbol === '*') { nt *= nextNum; } 
      else if (symbol === '/') { nt /= nextNum; }
      
      i++;
    }

//

    


// Function required to deal with negative numbers


// Something required to make answer display????
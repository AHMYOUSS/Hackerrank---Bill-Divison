# Hackerrank---Bill-Divison
function bonAppetit(bill, k, b) {
    var x = bill ; 
delete bill[k] ;

    var a = bill
    var sum = a.reduce(function(a, b) { return a + b; }, 0); 
    sum = sum/2; 
    if  ( sum == b){
        console.log('Bon Appetit')
    } else {
        console.log(b - sum)
    }

    }

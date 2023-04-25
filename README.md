/**
the whole course is about javascript
```
    https://www.youtube.com/watch?v=-xL3LXBiGfw&list=PLknwEmKsW8OuTqUDaFRBiAViDZ5uI3VcE&index=2
```

1 : Window , document , console : 

    How browser work ? what is DOM : document object model :
    control the browser from javascript
    window : {
        location : {
            href : "https://www.google.com"
        },
        history : {
            back : function() {
                // go back
            },
            forward : function() {
                // go forward
            },
            ...
        },
        ...
    }
    
control the page from javascript : 

    document : {
        html : {
            head : {
                title : "hello world"
            },
            body : {
                h1 : "hello world"
            }
        }
    }

control the console from javascript :

    console : {
        log : function() {
            // print to console
        },
        error : function() {
            // print to console
        },
        ...
    }

javascript Data types :

    dataType : {
        primitive : {
            string : "hello world",
            number : 123,
            boolean : true,
            null : null,
            undefined : undefined
        },
        nonPrimitive : {
            object : {
                name : "ahmed",
                age : 20
            },
            function : function() {
                // do something
            },
            array : [1,2,3,4,5],
        }
    }
    

    javascript variables : var , let , const


javascript conactenation :

    var name = "ahmed";
    var age = 20;
    var result;
    result = "my name is " + name + " and i am " + age; 
    or :
    result = `my name is ${name} and i am ${age}`;
    console.log(result);


javascript operators :

    + , - , * , / , % , ++ , -- , += , -= , *= , /= , %= , == , === , != , !== , > , < , >= , <= , && , || , ! , ? , : , = , += , -= , *= , /= , %= , ** , **= , << , >> , >>> , &= , |= , ^= , &&= , ||= , ?? , ??= , =>
    https://www.w3schools.com/js/js_operators.asp

    + : add
    - : sub
    * : mul
    / : div
    % : mod
    ** : power
    = : assign
    == : equal
    === : equal and same type
    != : not equal
    !== : not equal and not same type


javascript : cast data type : 

    auto cast to number : {
        var a = "10", b = "20";
        var x = a + b;   // 1020 | // type: string
        var y = +a + +b; // 30   | // type: number
        var z = a - b;   // -10  | // type: number

        var v = "ayman";
        +v // NaN => not a number
    }

    manual cast to number : {
        var a = "10";
        var x = Number(a);      // 30
        var y = parseInt(a);    // 30
        var z = parseFloat(a);  // 30
    }

    manual cast to string : {
        var a = 10;
        var x = String(a);      // "10"
        var y = a.toString();   // "10"
    }


javascript : 
    Objects Methods : {

        Number() : {
            Number.isInteger() : check if number is integer
            Number.isNaN() : check if number is NaN
            https://www.w3schools.com/js/js_number_methods.asp
        }

        Math() : {
            Math.abs() : absolute value
            Math.ceil() : round up
            Math.floor() : round down
            Math.round() : round to nearest
            Math.max() : return max number
            Math.min() : return min number
            Math.pow() : return power
            Math.sqrt() : return square root
            Math.random() : return random number
            https://www.w3schools.com/js/js_math.asp
        }
    }

 

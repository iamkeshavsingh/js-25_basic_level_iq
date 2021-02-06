# JavaScript 25 interview Questions - Basic Level

Ques 1: What is JavaScript?

    Motivation:
    Why to learn JavaScript?
    What kind of application can I make using JavaScript?

Ques 2: Difference between JavaScript and Java?

    SubQuestions:
    Ques 1: Difference between multi-thread and single-thread working?
    Ques 2: What is Asynchronous Programming?

Ques 3: What is event loop in JS?

    SubQuestions:
    What is output of the following code:
    (function(){
        for(var i=0;i<5;i++){
            (function(){
                setTimeout(function(){
                    console.log(i);
                },1000);
            })()
        }
    })()

Ques 4: Can you explain what happens in the compilation phase of JS?

    SubQuestions:
    Ques 1: Difference between Anonymous functions and named functions? (Which one is useful and when)
    Ques 2: Difference between let vs const vs var?
    Ques 3:What is Temporal Dead Zone?
    Ques 4: What is lexical scope?

Ques 5: Difference between strongly typed and weakly typed languages?

    Digging Deep in one phase which is famous in JS world: "In JS variables don't have types; Values does."

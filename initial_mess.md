## Disclaimer
#### This is a cluttered collection of new information I find about cpp


* this 
    In the body of a non-static member function, the keyword this is a \*prvalue expression whose value is the address of the     object for which the function is called 

    *READ ABOUT PRVALUE LATER

    What this points to can be modified but not the value of this.

    \*this = XY; // This is allowed
    this = &XY; // This is not allowed. Error: Expression is not assignable 

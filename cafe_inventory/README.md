1 What did you predict for Warmup.java, and what did it actually print? Explain the lines that surprised you.
    Expected OUTPUT:
    Two
    Three
    Actual OUTPUT:
    Two
    Three
    Explaination: there is no break statement in Switch and day=2, so it prints case 2 and then all other cases since there is no break statement.
    
2. What is the difference between the static variable totalProducts and the instance variable name?
    static variable totalProducts remain same for all the Objects of Product. Whereas instance variable name are different for each Product object. 
    static variable allocate just one memory and instance variable will be allocated per Object. 

3. What does the copy constructor do, and why does changing p2.name not change p1.name?
    copy constructor accept object of its class and create a new object with same value. changing p2 won't change p1 because p1 and p2 points to different memory location.
    
4. Why does Java force you to write (int) average when converting a double to an int, and what happens to the decimal part?
    The decimal part is removed and a whole number remains. When we convert double which is 64 bit to int which is 32 bit, there will be data loss. so the compiler requires
    a explicit cast to achknowdge the risk of data loss.
   

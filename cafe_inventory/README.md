1. What did you predict for Warmup.java, and what did it actually print? Explain the lines that surprised you. <br/>
    Expected OUTPUT: <br/>
    Two <br/>
    Three <br/>
    Actual OUTPUT:<br/>
    Two <br/>
    Three <br/>
    Explaination: there is no break statement in Switch and day=2, so it prints case 2 and then all other cases since there is no break statement.<br/><br/>
    
2. What is the difference between the static variable totalProducts and the instance variable name?<br/>
    static variable totalProducts remain same for all the Objects of Product. Whereas instance variable name are different for each Product object. <br/>
    static variable allocate just one memory and instance variable will be allocated per Object. <br/><br/>

3. What does the copy constructor do, and why does changing p2.name not change p1.name?<br/>
    copy constructor accept object of its class and create a new object with same value. changing p2 won't change p1 because p1 and p2 points to different memory location.<br/><br/>
    
4. Why does Java force you to write (int) average when converting a double to an int, and what happens to the decimal part?<br/>
    The decimal part is removed and a whole number remains. When we convert double which is 64 bit to int which is 32 bit, there will be data loss. so the compiler requires<br/>
    a explicit cast to achknowdge the risk of data loss.
   

* Addition and subtraction (Sec. 3.2)
* Constructing an arithmetic logic unit (Appendix C)
    * Building ALU

        <img src="./pics/image.png" width="50%">
        <img src="./pics/image3.png" width="50%">

        * Add, sub, and, or, nor
        * Set-on-less-than, overflow detection, zero detection
            * set-on-less-than
                
                <img src="./pics/image2.png" width="50%">

            * overflow detection

                <img src="./pics/image4.png" width="50%">

    * Fast adders
        * Poor Ripple Carry Adder

            <img src="./pics/image5.png" width="50%">

        * Cascaded carry look-ahead adder

            <img src="./pics/image6.png" width="50%">
            <img src="./pics/image7.png" width="50%">
        
        * Multiple level carry look-ahead adder

            <img src="./pics/image8.png" width="50%">

* Multiplication (Sec. 3.3, Appendix C)
    * Unsigned multiply
        * Partial Product -> shitf left
        * Multiplier -> shift left
        * So Partial Product & Multiplier could be concated

        <img src="./pics/image9.png" width="50%">

    * Signed multiply
        * rule1: Multiplicand sign extended
        * rule2: Sign bit
            * 0 -> 0 x multiplicand
            * 1 -> -1 x multiplicand
        * why rule2?

            <img src="./pics/image10.png" width="50%">

* Division (Sec. 3.4)
    * Use same component as multiplication

    <img src="./pics/image11.png" width="50%">
     
* Floating point (Sec. 3.5)
    * Representations
    * Addition and multiplication
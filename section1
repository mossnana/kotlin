fun main(args: Array<String>){
    // --- print and new line ---
    println("Hello World")
    
    // -- variable declaration ---
    // var : variable can assign everytime
    var epicVar = "Permpoon"
    var numOne = 1
    println(epicVar)
    println(numOne)
    numOne = 2
    println(numOne)
    // val : constrain
    val numTwo = 2
    // numTwo = 5 : error
    println(numTwo)
    // variable type declaration
    var numThree: Int? = 3
    var numThreePointOne: Float? = 3.1f
    var numFourInString: String? = "Four"
   	
    // -- String Method --
    // String Length Method
    println(epicVar.length)
    // String Get Char with index number
    println(epicVar.get(7))
    // String Compare : = will be return 0
    println(epicVar.compareTo("Hello World"))
    // String Concatenation
    var concateString = epicVar.plus("Hello World")
    
    // -- Array Method --
    var scoresArray = arrayOf(
    	1,
        2,
        3,
        4
    )
    var names = arrayOf("Batman", "Superman", "The Flash", "Wonder Woman")
    // output : [Ljava.lang.Integer;@1f32e575
    println(scoresArray)
    println(scoresArray[0])
    println(scoresArray[1])
    println(scoresArray[2])
    // .get() method
    // output : 1
    println(scoresArray.get(1))
    // output : Superman
    println(names.get(1))
    // .set() method : .set(index, "value")
    // output : Superman
    names.set(1, "The Man of Steel")
    
    // --- Data Type Convertion ---
    var i = 9
    var epicString: String
    // Convert int to Long
    var x: Long = i.toLong()
    // Convert Long to String
    epicString = x.toString()
    println(epicString)
    
    // --- Bitwise Operation ---
    // 128	64	32	16	8	4	2	1
    // 0	1	0	1	0	1	0	0
    var bitwiseExample = 84
    var bitwiseExampleTwo = 55
    // Shift Left
    // 128	64	32	16	8	4	2	1
    // 1	0	1	0	1	0	0	0
    println(bitwiseExample.shl(1))
    // Shift Right
    // 128	64	32	16	8	4	2	1
    // 0	0	1	0	1	0	1	0
    println(bitwiseExample.shr(1))
   	// xor operation
   	println(bitwiseExample.xor(bitwiseExampleTwo))
    // inverse operation
    println(bitwiseExample.inv())
    
    // --- Logical Operation ---
    // return Boolean
    println(bitwiseExample > bitwiseExampleTwo && bitwiseExampleTwo == bitwiseExample)
    
    // --- I/O ---
    // Input is alway String, Convert Before Use
    var ioVariable: Int = Integer.valueOf(readLine())
    println(ioVariable)
}

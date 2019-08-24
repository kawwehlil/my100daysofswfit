### Day 1 – variables, simple data types, and string interpolation 
`var operatingSystem = "macOS" `creates a new variables 
`var mortgageRemaining = 100_000` creates an integer called mortgageRemaining while var Dogbreed = "sam" creates a string
for multiple lines, using """ and do not put them onto the same line with the text

For example
>var str1 = """
>This goes
>over multiple
>lines
>"""

>var str1 = 
>"""
>This goes\
>over multiple\
>lines\
>"""

goes with `\`

Doubles and Blooen 

Double is different from integer, which has a fractioned number, such as ` var pi = 3.14`
Blooen returns true or false

Strings interpolation 

You can place any type of variable inside your string – all you have to do is write a backslash, \, followed by your variable name in parentheses. For example:

var score = 85
var str = "Your score was \(score)"
As you can see in the playground output, that sets the str variable to be “Your score was 85”.

You can do this as many times as you need, making strings out of strings if you want:

var results = "The test results are here: \(str)"

Constant
`let` lets a variable remain constant. for exmample `let mike = "mouse"`

finanally, you can make specific type by typing it out. 

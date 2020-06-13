#***_what-i-learned-in-week-4_***

##*_Booleans_* - represents one of two values: true or false.
It uses comparison operators such as :

| operators   |    Description   | Example |
|:----------:|:--------:|:------:|
| ==|  equal to | 	if (day == "Monday") |
| > |    greater than  |   if (salary > 9000)|
| <| less than | if (age < 18)   |
    
>When using the === operator, equal booleans are not equal, because the === operator expects equality in both type and value.


###**_Big comparison Operator Chart_**

| Operator  | Description  | Comparing | Returns  |
|---|---|---|---|
|  == | equal to  |  x == 8 | false   |
| ===  | equal value and equal type  | x === 5  | true   |
|	    |				      |x === '5'	    |  false  |
| !=  |  not equal | x != 8  | true  |
|  !=== | not equal value or not equal type  | x !== 5  | false  |
|		|								|x !== '5'    | true|
| >  | greater than  |  x > 8 | false  |
| <  |  less than |  x < 8 | true  |
|  >= | greater than or equal to  |  x >= 8 |  false |
| <=  | less than or equal to | x <= 8 | true|

#### **_Logical Operators_** 
Logical operators are used to determine the logic between variables or values.

| Operator | Description | Example|
| --- | --- | ---| 
| && | and | ( x < 10 && y > 1) is true |
|  ll | or | (x == 5 || y == 5) is false|
| ! | not | !(x == y) is true|


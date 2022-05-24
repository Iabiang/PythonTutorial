### Strings

#### Declaring Strings

&nbsp;  
`s = ''` &nbsp; &nbsp; &nbsp; # Type String  
`s = " " ` &nbsp; &nbsp; # Type String  
>`s = 'hello'`  
>`s = "hello"`   

&nbsp;  
*The `print()` function produces a more readable output,by omitting the enclosing quotes and by printing escaped and special characters*  

*`\` can be used to escape quotes*  
  
>print('doesn`\`'t') &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;# use `\'` to escape the single quote ; returns *doesn't*   
>print(`"`doesn't`"`) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; # or use double quotes instead  ; returns *doesn't*  
>print(`'`"Yes," they said.`'`) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;# or use double/single quotes to escape quotes ; returns *"Yes," they said.*  
>print("`\`"Yes,`\`" they said.") &nbsp; &nbsp; &nbsp; # returns "Yes," they said.

&nbsp;  

*`\n` adds a newline in the string*   

*`\t` adds tab or four spaces in the string*  

>print('First line.`\n`Second line.') 
>>Output:  
>>&nbsp;  
>>First line.  
>>Second line. 

>print("Dear Sir/Ma'am,`\n \t`Start line after tab.")
>>Output :  
>>&nbsp;  
>>Dear Sir/Ma'am,  
>>&nbsp; &nbsp; Start line after tab.  

&nbsp;  

*If you don’t want characters prefaced by `\` to be interpreted as special characters, you can use `raw strings` by adding an `r` before the first quote*

>print('C:\some\name') &nbsp; &nbsp; # here \n means newline!
>>Output :  
>>&nbsp;  
>>C:\some  
>>ame  

>print(r'C:\some\name') &nbsp; &nbsp; # note the r before the quote  
>>Output :  
>>&nbsp;  
>>C:\some\name  

&nbsp;  

#### Accessing Strings

s = 'Hello'  
&nbsp;  
>s[0] &nbsp; # character in position 0
>>'H' &nbsp; # Output  

>s[-1] &nbsp; # character in last position
>>'o' &nbsp; # Output


***NOTE: All these commands runs in ipython or any interactive interperter*** 

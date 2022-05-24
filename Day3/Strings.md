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

&nbsp;  
>print('doesn`\`'t') &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;# use `\'` to escape the single quote ; returns *doesn't*   
>print(`"`doesn't`"`) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; # or use double quotes instead  ; ; returns *doesn't*  
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

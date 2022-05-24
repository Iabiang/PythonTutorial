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

`s = 'Hello' ` 
&nbsp;  
>s[0] &nbsp; # character in position 0
>>'H' &nbsp; # Output  

>s[-1] &nbsp; # character in last position
>>'o' &nbsp; # Output

>s[1:3] &nbsp; # gives characters **[starting(*inclusive*) : upto_stop(*exclusive*) ]**
>>'el'  &nbsp; # Output

&nbsp;  

`s1='Hello'`

`s2='World'`  

>print(s1,s2) &nbsp; #Accessing the strings stored in variable s1 and s2
>>Hello World &nbsp; #Output

>print('This is the first word:',s1,'.This is the second word:',s2)
>>This is the first word: Hello .This is the second word: World

&nbsp;  

*Accessing using `f string`*

>print(f'This is the first word:{s1} .This is the second word:{s2}') &nbsp; # note the r before the quote
>>This is the first word:Hello .This is the second word:World

&nbsp;  

&nbsp;  
  
#### Concatenating Strings

*Strings can be concatenated with the `+` operator, and repeated with `*`*

>'hello'+'world'
>>'Helloworld' # Output

>2 * 'hello'
>>'hellohello' # Output  

&nbsp;  

***Declare `s` as a string first***

***`s.press_tab_button` : shows all the available strings methods***

(Note: *press_tab_button* is not a command you have to press the tab button)

&nbsp;  

***NOTE: All these commands runs in ipython or any interactive interperter*** 

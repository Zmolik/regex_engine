# regex_engine  
An extendable regex engine that can handle basic regex syntax, including literals (a, b, c, etc.), wild-cards (.), and metacharacters (?, *, +, ^, $). It compares regex notation with normal input and returns boolean value. Both values are imported as one divided by '|' (see example). 
  
**Learning outcomes**  
I learned about the regex syntax, practiced working with parsing and slicing, and get more familiar with boolean algebra and recursion.  

**Examples**    
Input:  '\.$|end.'    
Output:  True  

Input:  '3\+3|3+3=6'  
Output:  True    

Input:  'colou\?r|color'    
Output:  False    


This program is based on project from hyperskill.org: https://hyperskill.org/projects/114?track=2    


# regex_engine  
An extendable regex engine that can handle basic regex syntax, including literals (a, b, c, etc.), wild-cards (.), and metacharacters (?, *, +, ^, $). It compares regex notation with normale input and returns boolean value. Both values are imported as one divided by '|' (see example). 
  
This program is based on project from hyperskill.org: https://hyperskill.org/projects/114?track=2  
  
**Learning outcomes**  
I learned about the regex syntax, practiced working with parsing and slicing, and get more familiar with boolean algebra and recursion.  

# Example  
Input:        '\.$|end.'                Output: True  
Input:     '3\+3|3+3=6'             Output: True  
Input:       '\?|Is this working?'  Output: True  
Input:       '\\|\'                 Output: True  
Input: 'colou\?r|color'             Output: False  
Input: 'colou\?r|colour'            Output: False   

# Palindrome

## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### 1.Start the program.

### 2.Get the string value and read the string.

### 3.Use loop over the entire string and reverse it.

### 4.Use conditional statement for checking the reversed string.

### 5.Print whether the string is palindrome or not a palindrome.

### 6.End the program.

## Program:
```python
using System;  
    namespace palindrome  
    {  
        class Program  
        {  
            static void Main(string[] args)  
            {  
                string s,revs="";  
                Console.WriteLine(" Enter string");  
                s = Console.ReadLine();  
                for (int i = s.Length-1; i >=0; i--) //String Reverse  
                {  
                    revs += s[i].ToString();  
                }  
                if (revs == s) // Checking whether string is palindrome or not  
                {  
                    Console.WriteLine("String is Palindrome \n Entered String Was {0} and reverse string is {1}", s, revs);  
                }  
                else  
                {  
                    Console.WriteLine("String is not Palindrome \n Entered String Was {0} and reverse string is {1}", s, revs);  
                }  
                Console.ReadKey();  
            }  
        }  
    }
```

## Output:
![palindrome](https://github.com/Leann4468/Palindrome/assets/121165979/12c2b7b6-2995-4123-a50e-11804243fd2f)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.

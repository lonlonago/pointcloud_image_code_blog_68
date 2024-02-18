##  Python basics (a full set of nanny-level tutorials) 

###  Chapter One 

![avatar]( e91d6e62bc5444199bc1afa24f064143.png) 

 If you are asked to print a composition, a composition requires seven or eight hundred words, and I ask you to repeat the typing, do you want to copy it? This is very troublesome. If you replace this composition with an alias, it will be very convenient. This alias is a variable, so this is the function of a variable. Look at the picture specifically, don't understand it once, read it twice.   

![avatar]( 425056d8971e4f6c8aeeb85c4bb97eda.png) 

  In summary, a variable is a quantity that can change. Variables are used to distinguish between different data. They can point to a memory space and help us store some data 

Variable naming convention: 1. Must be a number or letter or downline composition. 2. Cannot start with a number, let alone a pure number. 3. Cannot use python keywords 4. Do not use Chinese 5. Do not be too long 6. Be meaningful 7. It is recommended to use downline naming or hump naming 

In summary, your variable name must be understandable. It is comfortable to read. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter One 

![avatar]( 935db4f4111d455f80ac53bba62fe91e.png) 

 Constants refer to data that remain unchanged throughout the operation, usually given their values directly in commands or programs. They can be certain quantities and information that do not change with time, or they can be characters or strings that represent a certain value, which are often used to identify, measure, and compare. In simple terms, it is like pai in mathematics, the speed of light in a vacuum in physics, Planck's constant h, and the basic charge e are all constants. All variables can be considered constants by uppercase, but there is no absolute constant.  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572303
 ```  


--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter One 

Data type: distinguish different data. Different data types should have different operations, numbers: ± */integer, int decimal, float text: show string: str (*****) representation : ‘’ “” ‘’’ ‘’’ “”" “”" operation: + left and right ends must be string, indicating string connection operation * A string can only be multiplied by a number, indicating the number of times the string is repeated 

![avatar]( 490cb5b902b849c5a9f3daf56112bf98.png) 

 Boolean (bool): Conditional judgment, there are two main Boolean values: True True, True Proposition False False, False Proposition 100 > 30 - > True   

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574522486
 ```  


--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter One 

![avatar]( 512c43cb24214ab581190fdfebd3429f.png) 

 The programs we often use will have programs that interact with users, such as web page login, user interaction functions such as entering your account number and password. Let's write a simple user input and output program code: follow the experience, user login  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453138
 ```  
calculator 

![avatar]( c19ce2e94d904c25b64ce34531a9571c.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453138
 ```  
Summary: Variable = input (prompt) will first display the prompt on the screen, and the user will enter the content. Then give the user input to the previous variable, and the result obtained by pit: input () must be string. 

How to convert string to numeric type py Basic data type: Use whoever you want to convert xxx to str = > int int (str) 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( 543532ba43754158813eb7320d42c68d.png) 

 Set collection, set collection is unordered and cannot be hashed: When the set collection in python is used for data storage, the data needs to be hashed, and the data stored according to the calculated hash value must be hashable. Variable data types, list, dict, set can be hashed: immutable data types, int, str, tuple, bool.  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579419
 ```  
![avatar]( 2805b1baa40946d28a400f02120eef30.png) 

 Add increase  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579419
 ```  
Remove Delete, want to modify. Delete first. Then add a for loop for query 

![avatar]( f3bc11d177484365b0fb2a0e005af265.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579419
 ```  
Summarize: set collection, set collection is unordered add add remove delete for loop, used for query, the key is to understand the hash, not hash: python set collection for data storage. Need to hash the data, according to the calculated hash value to store data set set set requires that the data stored must be hashable. Variable data types, list, dict, set hashable: immutable data types, int, str, tuple, bool. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

String: A collection of characters is a string (String). Strings in Python must be surrounded by double quotes "" or single quotes "'. 1. String formatting problem% s string placeholder% d placeholder integer% f placeholder decimal 

![avatar]( 95bf03337a72472daf4af0c52f2b40e1.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574531322
 ```  
![avatar]( ad3e25d5cce6489493010f3043a25f61.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574531322
 ```  
Slicing: extracting a part of a string 

![avatar]( f7e7e998788a4dc89064fb4bac49146f.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574531322
 ```  
You can add steps to slices to control the direction of slices 

![avatar]( 10dcabeaadad4656a5bd3be5e133fc34.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574531322
 ```  
Summarize: 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

*** String operations generally do not affect the original string. Generally, a new string is returned. 

Capitalize string case conversion 

![avatar]( b045a68b440d46a6ac7ca22c3831ca73.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574595179
 ```  
Capitalize the first letter of the title word 

![avatar]( 1d896f106cd2443cbc28f9278a339ba1.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574595179
 ```  
![avatar]( d0249e499e6a437cad19effd8b309b2c.png) 

 Lower to lower case  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574595179
 ```  
UPPER Convert all letters to capital letters 

![avatar]( 87a9a2fa49834b7f8ce8d0485f0073b8.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574595179
 ```  
How to ignore case to judge = > upper (), the case column realizes ignoring case English input verification code: 

![avatar]( 121e4408756441ec8f5d14a5341df9bb.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574595179
 ```  
Summary: The string operation does not change the original string. Capitalize string case converts the first letter of the title word to uppercase lower to lowercase upper to uppercase all letters 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

Most of the content of this chapter is to remember. There are not many things to understand. In the later studies, the content of this chapter will be often used 

(* Represents importance). 

![avatar]( f4c784aec8e24d6c95790d74940b6871.png) 

  Int, float, bool str () list () tuple () set (*) dict (***) bytes () operator () file operation (***) int: integer, addition, subtraction, multiplication, division, size comparison  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596145
 ```  
![avatar]( 5121f987d0be4d1c8f16c4f8fbd4fba6.png) 

 Float: decimal, floating point   

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596145
 ```  
Decimal: The range of data is infinite. Integer: It can be expressed clearly within a specific interval. 0~ 1 computer is a binary product: 0, 1 computer represents a decimal number with errors. 

Bool: used for conditional judgment, value range: True, False conversion between underlying data types 

![avatar]( 882ad453af8a461aa64d75feda8bf03c.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596145
 ```  
Summary: int: integer, addition, subtraction, multiplication and division, size comparison, computer is a binary product: 0, 1 computer indicates that a decimal number is subject to error. In Python, all non-zero numbers are True, zero is False. In Python, all non-empty strings are True, empty strings are False. In summary, in Python's basic data types, everything that represents empty is False, and everything that is not empty is True. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( 199366662a2a45f7bd6ac941e0f6c272.png) 

 Other operations (supplementary) sorting of the list, the list will be saved in the order you stored, sort the list in ascending order reverse: flip  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574564288
 ```  
nesting of lists 

![avatar]( 324b0cb834b44d91939c7f9b3811a818.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574564288
 ```  
List of circular deletion, prepare a temporary list, responsible for storing the content to be deleted, record the content to be deleted, and go to the original list for deletion. 

![avatar]( df6473fb596e4f13a53e53068fcca228.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574564288
 ```  
Summary: sort sort the list in ascending order, reverse flip, pay attention when looping, prepare a temporary list, responsible for storing the content to be deleted, record the content to be deleted, and go to the original list to delete. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

Tuple tuple, feature: immutable list, running the following code will report an error, 'tuple' object does not support item assignment means that tuple does not support your modification operation. 

![avatar]( 0081c8a08f5846bcbeb9dd9309f7b6a1.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580510
 ```  
![avatar]( 82ef31efde7f4990a55fd0534fd36796.png) 

 You fixed some data. No external modification is allowed. If a tuple has only one element (*), it is str. If you have to turn it into a tuple, you need to add a comma at the end of the element. You can check the type with type.  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580510
 ```  
Regarding the immutability of tuples (pits), the memory address cannot be changed. You can understand it as you or you, you changed clothes! The essence is unchanged. 

![avatar]( 0225d09a88da4c25b81944d4d42adfbe.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574580510
 ```  
Summary: tuple, feature: immutable list. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( cc648dbd153543c8a88df20f458d51fa.png) 

 Intersection, union, difference &, intersection |, union -, difference  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574532754
 ```  
![avatar]( c36624b48cd7475c816584605ed79b81.png) 

 Important role: can remove duplication  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574532754
 ```  
Summary: &, intersection |, union union -, difference difference set, important role: using the characteristic that the set cannot be repeated, the duplication can be removed 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( 7be55020b1e44b5bb214b0f321bfb085.png) 

 Dictionaries, first of all, dictionaries store data in the form of key-value pairs. The representation of dictionaries is: {key: value, key2: value, key3: value}  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572482
 ```  
Feature, the key of the dictionary must be a hashable data class (immutable) The value of the dictionary can be any data type, the following two cases 

![avatar]( 574a06e77af54c04b222fde6c139290d.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572482
 ```  
Summary: First of all, the dictionary stores data in the form of key-value pairs. The representation of the dictionary is: {key: value, key2: value, key3: value} The key of the dictionary must be a hashable data class (immutable) The value of the dictionary can be any data type 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( a2447671cca14602996ecd46bd103c1f.png) 

 The addition, deletion and revision of the dictionary  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
![avatar]( 931be1f454ec4c1ca560031d34a9c418.png) 

 Modify, at this time, there is already jay in the dictionary. At this time, the modification operation is performed  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
![avatar]( af88b24ea08e4ed8b3adea45df72e3b6.png) 

 Setdefault sets the default value. If you already have tom before. setdefault doesn't work  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
![avatar]( d0397354c0c2497a984bd08c18777761.png) 

 Delete, delete according to the key  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
![avatar]( ba74877464be4e0c90c1af1c28a46434.png) 

 Query dic [] if the key does not exist. The program will report an error. When you are sure that your key is OK, you can use get if the key does not exist. The program returns None. When you are not sure about your key, you can use  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
None is simply empty, meaning nothing 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
![avatar]( 4cce290e3da246589fe53cc2d15710de.png) 

 Example:  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574559125
 ```  
When you input can't find it, and output none, it will output that there is no such person in our village. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

The loop of the dictionary, looking directly at the picture and looking at the code 

![avatar]( f154689ca24f44e38c7e9336a6587960.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572917
 ```  
Tuples or lists can perform this operation. The operation is called deconstruction (unpacking). 

Dictionary nesting 

![avatar]( 4815bfbb1c5e42afa8e727d2bc1584bf.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572917
 ```  
It's very simple, just remember...... 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

![avatar]( 75103475df8e4a61a1d959b9e5295322.png) 

 Supplement. Circular deletion of dictionaries  

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574563012
 ```  
The purpose of the code is to delete all people with large surnames. Analysis: If we directly delete the people with large default values, an error will be reported: Say that the size of the dictionary has changed, the way is to store the large ones in a list, and then delete them. In the end, what's left of the dictionary is the result we want. Let me tell you the code, I don't know what I said. It's the most important thing to understand yourself... 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

Scientists used diodes to make a binary '010101 'into decimal to become the Arabic numerals we know. Computers can't just be used for numerical calculations, we also need to read novels and read words. So smart scientists use different methods to replace words, just like the telegram beep beep in the anti-Japanese drama, the Morse password is based on the leverage of the ‘- - . .’ to transmit information. The earliest Morse password, one by one, each different, this computer will not work on that computer. At this time, the United States said that one family is the same, and it cannot be made, and it must be unified. The ascii code came out: ascii = > arranged 128 characters. It only needs 7 zeros and 1s to represent it. 01111111 = > 1 byte = > 8 bits The following are more and more forms: 1.0 1 < = > 10101010 = > binary is converted to decimal < = > 88 How computers store text information 1000000 < = > a 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957456451
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957456451
 ```  


--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

Operator: 

![avatar]( 56ec84dbd5d6479bbd29c90c94a1fd2a.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574566856
 ```  


--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

Operator: 

![avatar]( 201c21c16d9d4a5ea3420963b89510ca.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574518797
 ```  


--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

File operation, first prepare a text file: xxx.txt open (file path, mode = ", encoding =") 

File path: 1. absolute path d:/test/xxxx.txt 2. relative path, relative to the folder where your program is currently located.../previous layer folder mode: r: read read w: write write a: append write b: read and write non-text files - > bytes 

![avatar]( ecc59612fd2f4d408b8b1d366bc0b943.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574539909
 ```  
Encoding is used to open the text, but not to open the picture. 



--------------------------------------------------------------------------------

##  Python basics (a full set of nanny-level tutorials) 

###  Chapter II 

File operation: read strip: remove the whitespace at the left and right ends of the string. Spaces, newlines, tabs read: read all readline: read line by line readlines: read out and put into the list for in: read each line of data from it 

![avatar]( 31591f30ba6f435b99b150bbd47a4c5e.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574545192
 ```  
Summary: for xx in xx: focus 



--------------------------------------------------------------------------------


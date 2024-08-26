# Dict-data-type

-> Dict is a predefined data class, dict catagery data type.
-> Purpose: To store data in a (key:value) format.
   Key values: must be unique.
   values of value: can be unique also duplicate.
-> notation: {}
-> syntax: varname = {key1:value1, key2:value2 ......., keyn:valuen}
-> dict are two types:
   1) empty dict
      syntax: d = {}
            or
      syntax: d = dict(iterative object)
-> dict follows insertion order.
-> dict don't have idexing, so we can't perform idexing and slicing.
-> In dict keys are consider as idexes.

      **memory management**
-> If we try enumerate funtion to print dict values, It prints idexes and key values don't print values of value.
eg: d = {10:'python',12: 13, 14: 7.8, 16: 3+4j, 7.8:34}
    for x,y in enumerate(d):
        print(x,'------>',y)
    output:
    0 ------> 10
    1 ------> 12
    2 ------> 14
    3 ------> 16
    4 ------> 7.8
-> Enumerate function can take only 2 orguments so we can't print values of value.
-> syntax to add,replace a key:value to dict: d[key] = value

   **predefined functions**
->1)clear()
=>Syntax:   dictobj.clear()
=>This Function is used for Removing all the (Key,Value) from dict object
=>When we call this Function w.r.t empty dict then we get None as Result

2) pop()
**************************************************************************************************************************************************
Syntax:    dictobj.pop(Key)
=>This Function is used for Removing (Key,Value) from Non-empty Dict Object
=>If the Value of Key does not Exist then we get KeyError

3) popitem()
**************************************************************************************************************************************************
Syntax:  dictobj.popitem()
=>This Function is used for Removing Last (Key,value) from Non-empty dict object
=>When we call this function on empty dict object then we get KeyError.

4) copy()
**************************************************************************************************************************************************
Syntax:   dictobj2=dictobj1.copy()
=>This Function is used for Copying the content of One Dict object to another dict object(Implementation of Shallow Copy)


5) get()--Most Imp
**************************************************************************************************************************************************
=>Syntax:    Varname=dictobj.get(Key)
=>This Function is used for Obtaining Value of Value by passing the value of Key
=>If the Value of Key does not exist then we get None as Result
				OR
=>Syntax:     dictobj[Key]
=>This Syntax also gives Value of Value by passing Value of Key
=>If the Value of Key does not exist then we get KeyError

6) keys()
**************************************************************************************************************************************************
Syntax:      varname=dictobj.keys()
=>This Function is used for Obtainng Values of Key and placed in varname and whose type <class,'dict_keys'>

7) values()
**************************************************************************************************************************************************
Syntax:      varname=dictobj.values()
=>This Function is used for Obtainng Values of Value and placed in varname and whose type <class,'dict_values'>

8) items()
**************************************************************************************************************************************************
Syntax:      varname=dictobj.items()
=>This Function is used for Obtainng (Key,value) from dict object and placed in varname and whose type <class,'dict_items'>


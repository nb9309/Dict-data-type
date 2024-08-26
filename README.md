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

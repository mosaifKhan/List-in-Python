# List-in-Python
In this i have covered all the functions of list in python 
Python 3.8.5 (tags/v3.8.5:580fbb0, Jul 20 2020, 15:43:08) [MSC v.1926 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
>>> #List#
A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements. 
Each element or value that is inside of a list is called an item. 
Just as strings are defined as characters between quotes, lists are defined by having values between square brackets [ ].


>>> nums = [45,677,24,6,78,24,567,56]
>>> 
>>> nums
[45, 677, 24, 6, 78, 24, 567, 56]
>>> nums [2]
24
>>> nums [5]
24
>>> nums[3]
6
>>> nums [-3]
24
>>> nums [2:]
[24, 6, 78, 24, 567, 56]
>>> nums [3:1]
[]
>>> nums [3:5]
[6, 78]
>>> names = ['Mosaif', 'Love', 'Sweet', 'Perdon']
>>> names
['Mosaif', 'Love', 'Sweet', 'Perdon']
>>> print (names)
['Mosaif', 'Love', 'Sweet', 'Perdon']
>>> Names = ["Mosaif, Sweet, Love, Perdon"]
>>> 
>>> 
>>> Names
['Mosaif, Sweet, Love, Perdon']
>>> values = [5.7, 'Mosaif', 42]
>>> 
>>> values
[5.7, 'Mosaif', 42]
>>> mil = [Names, values, nums]
>>> mil
[['Mosaif, Sweet, Love, Perdon'], [5.7, 'Mosaif', 42], [45, 677, 24, 6, 78, 24, 567, 56]]
>>> sk = [nums, Names]
>>> sk
[[45, 677, 24, 6, 78, 24, 567, 56], ['Mosaif, Sweet, Love, Perdon']]
>>> 
>>> sk.append (23)
>>> 
>>> sk
[[45, 677, 24, 6, 78, 24, 567, 56], ['Mosaif, Sweet, Love, Perdon'], 23]

>>> sk.insert (8,111)
>>> sk
[[45, 677, 24, 6, 78, 24, 567, 56], ['Mosaif, Sweet, Love, Perdon'], 23, 111]

>>> sk.insert (1,'Raj')
>>> sk
[[45, 677, 24, 6, 78, 24, 567, 56], 'Raj', ['Mosaif, Sweet, Love, Perdon'], 23, 111]
>>> sk.insert (2,000)
>>> sk
[[45, 677, 24, 6, 78, 24, 567, 56], 'Raj', 0, ['Mosaif, Sweet, Love, Perdon'], 23, 111]

>>> nums.insert (2,'aap')
>>> nums
[45, 677, 'aap', 24, 6, 78, 24, 567, 56]

>>> nums.remove ('aap')
>>> nums
[45, 677, 24, 6, 78, 24, 567, 56]

>>> nums.pop (2)       //# The pop stands for the number removed with the help of sequence if the sequence is not putted it will remove from the end/last of the list.
24
>>> nums
[45, 677, 6, 78, 24, 567, 56]
>>> nums.pop ()
56
>>> nums
[45, 677, 6, 78, 24, 567]

>>> del nums [3:5]      //# del stands for delete the multipal numers at a time also it can remove number from (where to where).
>>> nums
[45, 677, 6, 567]

>>> nums.extend ([36,783,8,995,377,37,83])  //# extends for add the value in the end of the list values.
>>> nums
[45, 677, 6, 567, 36, 783, 8, 995, 377, 37, 83]
>>> del nums [3:6]
>>> nums
[45, 677, 6, 8, 995, 377, 37, 83]
>>> nums.extend ([94,67,27,89,348,89,27,688])
>>> nums
[45, 677, 6, 8, 995, 377, 37, 83, 94, 67, 27, 89, 348, 89, 27, 688]

>>> nums
[45, 677, 6, 8, 995, 377, 37, 83, 94, 67, 27, 89, 348, 89, 27, 688]
>>> del nums [4:8]
>>> nums
[45, 677, 6, 8, 94, 67, 27, 89, 348, 89, 27, 688]

>>> nums.insert (2,90)      //# insert for add the value at located position.
>>> nums
[45, 677, 90, 6, 8, 94, 67, 27, 89, 348, 89, 27, 688]

>>> min (nums)      //# min for find the value which is minimum of the list.
6

>>> max (nums)      //# max for find the value which is maximum of the list.
688

>>> sum (nums)      //# sum for add all the values of the list.
2255

>>> nums.sort ()    //# sort for to arrenge the value in asending form of the list.
>>> nums
[6, 8, 27, 27, 45, 67, 89, 89, 90, 94, 348, 677, 688]
>>> 

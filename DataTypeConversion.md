# ডাটাটাইপ কনভার্সন 

ডাটাটাইপ কনভার্সন বলতে ভ্যারিয়েবল কে এক টাইপ থেকে অন্য টাইপ এ কনভার্ট করা বুঝায়। একে টাইপ কাস্টিং ও বলা হয়ে থাকে।

পাইথন এ টাইপ কাস্টিং এর জন্যে কিছু বিল্টইন ফাংশন বানানো আছে। আমরা চাইলে সহজেই সেগুলো ব্যাবহার করতে পারি।

# ইন্টেজার এ কনভার্সন 
স্ট্রিং অথবা ফ্লোট থেকে ইন্টেজার এ কনভার্ট করার জন্য ``` int() ``` ফাংশন ব্যাবহার করা হয়। 
```python
// String to Integer Conversion
>>> a= "123"
>>> b= int(a)
>>> print(b)


// float to Integer Conversion
>>> a= 12.56
>>>b=int(a)
>>>print(b)
```
বিঃ দ্রঃ  স্ট্রিং থেকে ইন্টেজার এ কনভার্ট এর সময় খেয়াল রাখতে হবে স্ট্রিং এ যাতে কোনো নননিউমেরিক ক্যারেকটার না থাকে।  

# ফ্লোট এ কনভার্সন 
স্ট্রিং অথবা ইন্টেজার থেকে ফ্লোট এ কনভার্ট করার জন্য ``` float() ``` ফাংশন ব্যাবহার করা হয়।
```python
// String to float Conversion
>>> a= "123.456"
>>> b= int(a)
>>> print(b)


// Integer to float Conversion
>>> a= 12
>>> b=float(a)
>>> print(b)
```
বিঃ দ্রঃ এক্ষেত্রেও স্ট্রিং থেকে ফ্লোট এ কনভার্ট এর সময় খেয়াল রাখতে হবে স্ট্রিং এ যাতে কোনো নননিউমেরিক ক্যারেকটার না থাকে এবং একাধিক দশমিক পয়েন্ট না থাকে। 

এবার একটু ভাবুনতো স্ট্রিং এর ভেতর যদি দশমিকযুক্ত সংখা থাকে এবং তা ইন্টেজার এ কনভার্ট করার প্রয়োজন হয় তাহলে কি int() ফাংশন ব্যাবহার করলেই হবে ? উত্তর হবে না । সেক্ষেত্রে স্ট্রিং কে প্রথমে ফ্লোট এ এবং ফ্লোটকে ইন্টেজার এ কনভার্ট করতে হবে।
```python
>>> a = "123.456"
>>> b = float(a)
>>> c = int(b)
>>> print(c)
```

# স্ট্রিং এ কনভার্সন
যে কোনো ভ্যরিয়েবল কে স্ট্রিং এ কনভার্ট করার জন্য কোনো প্রকার বিধিনিষেধ ছাড়াই ```str()``` ফাংশন ব্যাবহার করবো। 
```python
>>> a = 123
>>> b = str(a)
>>> print(b)

আমরা যখন ```print()``` ফাংশন এর ভেতর একাধিক ভ্যারিয়েবল লিখি তখন স্ট্রিং কনভার্সন ব্যাবহার করতে হয়। 
```python
>>> a= 152.123
>>> b= 123
>>> print("Float = "+ str(a)+" Integer = "+ str(b))
```

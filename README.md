# class_2_py
Practice on data type of python
#str
from distutils.log import info


a = str(1)
print(type(a))
print(type("Hello world"))
a1 = 10
print(type(a1))
a2 = 10.5
print(type(a2))
a3 = 10j
print(type(a3))
#list
info = ["Rahim",5,5.5,["Korim",5,5.6]]
print(type(info))
for i in info:
    print(i,type(i))
info1 = ("rahim", 5, 3.9, ["3", "korim", 9.9])
print(type(info1))
#dict
person = {"name": "Rahim", "age": 34, "height": 5.5, "childs": [{"name": "Rafiq", "age": 13, "height": 4.5}, {"name": "Sofiq"}]}
print(type(person))
students = {"Rahim", "Karim", "Noman", "Hasib", "Rahim", "Rahim", "Noman"}
print(students)
print("Abul" in students)
#bool
students = [{"name": "Rahim", "age": 13, "gender": "Male"}, {"name": "Rahima", "age": 15, "gender": "Female"}]
print("Rahim" is 13)
bytes, bytearray, memoryview
number_of_packets = 5
number_of_packets = None
print(type(number_of_packets))

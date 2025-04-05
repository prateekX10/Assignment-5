# ASSIGNMENT - 5
# TASK - 1

dic = {'Alice': '90'}
name = input("Enter student's name: ")


if name in dic:
  print(name,"'s marks: ", dic[name])
else:
  print("Student not found")


# TASK - 2
original_list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
extracted_elements = original_list[0:5]
print("First five elements from the list: ", extracted_elements)
print("reverse list of the first five elements: ", extracted_elements[::-1])


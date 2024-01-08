# class Dog:
    
#     def __init__(self, name, age):
#         self.name = name    
#         self.age = age
    
    
#     def get_name(self):
#         return self.name
    
    
#     def get_age(self):
#         return self.age
    
#     def set_age(self, age):
#         self.age = age      


# d = Dog("Tim", 23)
# d.set_age(34)
# print(d.get_age())



# class Student:
#     def __init__(self, name, age, grade):
#         self.name = name
#         self.age = age
#         self.grade = grade
        
        
#     def get_grade(self):
#         return self.grade
    
    
    
# class Course:
#     def __init__(self, name, max_students):
#         self.name = name
#         self.max_students = max_students
#         self.students = []

#     def add_student(self, student):
#         if len(self.students) < self.max_students:
#             self.students.append(student)
#             return True
#         return False
    
#     def get_average_grade(self):
#         value = 0
#         for student in self.students:
#             value += student.get_grade()
        
#         return value / len(self.students)
        
        
# s1 = Student("Tim", 19, 95)
# s2 = Student("1023", 24, 97)
# s3 = Student('Jill', 19, 65)        
        
        
# course = Course("Science", 2)
# course.add_student(s1)
# course.add_student(s2)
# print(course.add_student(s3))
# print(course.get_average_grade())
        
        
        
# CLASS INHERITANCE


# class Pet:
#     def __init__(self, name, age):
#         self.name = name
#         self.age = age
        
        
#     def show(self):
#         print(f"I am {self.name} and I am {self.age}")




# class Cat(Pet): 
#      def __init__(self, name, age, color):
#          super().__init__(name, age)
#          self.color = color
     
     
     
#      def speak(self):
#         print("Meow!!")
        
#      def show(self):
#          print(f"I am {self.name} and I am {self.age} years old and my color is {self.color}")   
    
        
# class Dog(Pet):
    
#     def speak(self):
#         print("Bark!!")
        
        

# p = Pet('Tim', 19)
# p.show()

# c = Cat('Bill', 12, 'Turquoise')
# c.show()
# c.speak()

# d = Dog('Jill', 9)
# d.show()
# d.speak()
        
        
        

# STATIC, CLASS METHODS, CLASS ATTRIBUTES
  
#   CLASS ATTRIBUTES

# class Person:
#     number_of_people = 0
    
#     def __init__(self, name):
#         self.name = name
#         Person.number_of_people += 1
        
# p1 = Person("Tim")
# print(Person.number_of_people)
# p2 = Person('1023')
# print(Person.number_of_people)
        
        
# CLASS METHODS

# class Person:
#     number_of_people = 0
    
#     def __init__(self, name):
#         self.name = name
#         Person.add_person()
       
       
#     @classmethod   
#     def number_of_people_(cls):
#         return cls.number_of_people
    
    
#     @classmethod
#     def add_person(cls):
#         cls.number_of_people += 1


# p1 = Person("Tim")
# p2 = Person('1023')
# print(Person.number_of_people_())
            
   
   
# STATIC METHODS
     
        
class Math():
    
    @staticmethod
    def add5(x):
        return x + 5
    
    @staticmethod
    def add10(x):
        return x + 10
    
print(Math.add10(13))
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        

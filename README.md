# ООП

------------


#### - Почти всегда оперируем объектами в программе и это удобнее делать через классы
#### - Класс - это шаблон, blueprint по которому в дальнейшем могут формироваться объекты 
#### - в этом шаблоне могут быть как перемены, данные (атрибуты класса) так и функиции(методы) 

### пример класса 
    class Cat:
		def __init__(self, color, age, name):
			self.color = color
			self.age = age
			self.name = name
		def draw():
			print(f"{self.name} is f{self.color} and is f{self.age} old.")

#### Создание объекта
		pet = Cat("Red", "7", "Fluffy")
		pet.bark()  

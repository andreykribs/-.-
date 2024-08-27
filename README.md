immutable_var = 1, 2, 3, "a", "b"
print(immutable_var)
# кортеж - это неизменяемая упорядоченная коллекция, может держат ьв себе разные типы данных

mutable_list = ["cat", "go", "dog", 1, 2, 3, "horizon"]
print(mutable_list)
# просили в задании изменить элементы списка, изменил ниже
print(mutable_list[6])
mutable_list[6] = "big"
print(mutable_list)

![resim_2022-10-26_171949090](https://user-images.githubusercontent.com/45060751/198051430-6c0de6bb-0745-4f30-81cc-e793cd4e8194.png)
# Patika

Burada sıralanmamış bir dizi üzerinde nasıl binary search tree algoritmasının ilerlediğini anlatacağım. 

1- ilk olarak 7 sayısını yerleştiririz. 

2- Daha sonra gelen 5 sayısının yerini belirlemek için 7 sayısını referans alarak bu sayıdan küçük olduğu için 7'nin soluna yazarız.

3- Sıradaki 1 sayısı da 5'ten küçük olduğu için 5'in solunda bir dala yazarız.

4- 8 sayısı root noktamız olan 7'den büyük olduğu için bu sefer sağına eklemek durumundayız.

5- 3 sayısı 7'den küçük, bir sonraki daldaki 5'ten küçük, bir sonraki daldaki 1'den büyük olduğu için 1'in sağına yazarız.

6- 6 sayısı 7'den küçük, solundaki 5'ten büyük olduğu için 5'in sağında yazılmalıdır.

7- 0 sayısı 7'den küçük, bir sonraki daldaki 5'ten küçük, bir sonraki daldaki 1'den de küçük olduğu için 1'in soluna yazarız.

8- 9 sayısı 7'den ve 8'den büyük olduğu için sağ dalda en alt kısımda kendisine yer bulur.

9- 4 sayısı 7'den küçük, bir sonraki daldaki 5'ten küçük, bir sonraki daldaki 1'den büyük olduğu için 1'in sağına yazarız, ancak sayı 3'ten de büyük olduğu için 3'ün de altında sağa yazılması gerekir.

10- Son olarak 4 sayısı 7'den küçük, bir sonraki daldaki 5'ten küçük, bir sonraki daldaki 1'den büyük olduğu için 1'in sağına yazarız, ancak sayı 3'ten küçük olduğu için 3'ün soluna yazılmalıdır.

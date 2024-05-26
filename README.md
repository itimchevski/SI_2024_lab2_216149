Иван Тимчевски 216149
![image](/c/Users/Ivan/Downloads/SI_2024_lab2_216149/graph.png)

<h1> Цикломатска комплексност </h1> <p> Цикломатска комплексност според 
нацртаниот граф ми излегува 8. М=Е-Н + 2п </p> <h1> Тест случаи според 
критериумот Every Branch, користам 4 случаи.</h1> <p> - тест во случај на 
allitems == нул </p> <p> - тест случај кога getBarcode е различно од нулл или 
нема должина </p> <p> - тест случај кога sum е помала од вр. </p> <h1> Тест 
случаи според Multiple Condition </h1> <p> - item.getName() == null || 
item.getName().length() == 0 </p> <p> item.getPrice() > 300 && item.getDiscount() 
> 0 && item.getBarcode().charAt(0) == '0' </p> <h1> Објаснување за напишаните 
unit tests </h1> <p> - testAllItemsNull кога allItems == null</p> <p> - 
getBarcode!=null или должина: name = 0 </p> <p>Случај кога sum <= payment </p> 
<h1>Тест за Every Branch </h1> <p> - name е null или 0 </p>
<p> - price > 300 И  има discount</p>


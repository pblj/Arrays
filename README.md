Массивы
Массив(Array) – это набор элементов одного типа в непрерывной области памяти. Массивы бывают динамические и статические. Статическим называется массив, количество элементов которого можно задать только целочисленным константным значением и только на этапе написания кода, размер статического массива невозможно изменить после компиляции. Размер динамического массива может быть задан переменным значением во время выполнения программы. Предварительно это переменное значение можно вычислить или ввести с клавиатуры. Как статические так и динамические массивы бывают одномерные, двухмерными, трехмерные и т.д. (многомерными). 
Пока мы будем изучать только одномерные статические массивы. Для объявления массива нужно указать тип его элементов, имя массива, количество элементов массива следующим образом: 
Type name[SIZE];
Type – тип элементов массива. Элементы массива могут быть любого существующего типа. 
Name – имя массива. Для именования массивов используются такие же идентификаторы, как и для именования переменных.
SIZE – количество элементов массива константа.
Обращение к элементам массива
Элементы массива являются самыми обычными переменными. Следовательно, обращаться к ним можно на чтение и на запись. Для обращения к элементу массива нужно указать его номер в квадратных скобках после имени массива. Элементы массива нумеруются с 0 и именно поэтому номер последнего элемента на единицу меньше количества элементов.
Для обращения к элементам массива очень удобно использовать цикл FOR поскольку у него есть счетчик -I- , который можно использовать в качестве индекса элемента. 
При объявлении массива под него просто выделяется память которая просто заполнена мусором. Для того чтобы убрать мусор его нужно проинициализировать. Для инициализации массива нужно перечислить значения его элементов в фигурных скобках через запятую.

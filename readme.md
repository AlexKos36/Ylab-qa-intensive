1.Магазин принимает накопительные скидочные карты и при своем расчете учитывает количество баллов, по которому начисляет процент скидки: От 0 до 100 баллов - скидка 1% От 101 до 500 баллов - скидка 3 % От 500 до 2000 баллов - скидка 5% От 2001 баллов - скидка 10%
Задание: Составить такой набор тестовых данных для магазина (в формате количество баллов - ожидаемая скидка), при котором мы будем знать, что в соответствии со своими накопленными баллами покупатель получит верную скидку.

a) 0 - 100 баллов  (скидка 1%)

b) 101 - 499 баллов (скидка 3%)

c) 501 - 2000 баллов (скидка 5%)

d) 2001 и более баллов (скидка 10%)

500 баллов - по условиям, которые предоставил магазин, данное значение входит в два эквивалентных класса, что вызывает у программы "накопительных скидочных карт" неопределенное значение скидки с данным количеством баллов (3% или 5%). Для того чтобы, значение скидки с данным количеством баллов было точным, необходимо отнести ее к одному из классов, а втором уменьшить или увеличить (в зависимости от того в какую группу определят данное значение) на единицу, количество баллов, которые будут соотноситься с величиной скидки, для исключения дублирования данного значения.   

2.Наш сайт представлен на двух языках: русский (RU) и английский (EN). Из требований следует, что сайт будет открываться в браузерах Opera и Firefox, на операционных системах Windows 10 и Ubuntu 20.04, а также на устройствах с операционной системой Android 10 в браузере Chrome.
Задание: Укажите минимальный набор конфигураций (браузер, ОС, язык сайта), который вы бы использовали для тестирования данного сайта.

  Opera,  Windows 10, RU
  
  Opera,  Windows 10, EN
  
  Opera,  Ubuntu 20.04, RU
  
  Opera,  Ubuntu 20.04, EN
  
  Firefox,  Windows 10, RU
  
  Firefox,  Windows 10, EN
  
  Firefox,  Ubuntu 20.04, RU
  
  Firefox,  Ubuntu 20.04, EN
  
  Chrome, Android 10, RU
  
  Chrome, Android 10, EN

3.Ответьте на вопросы:

- Какой категории ui-элементов относится данный элемент? (см. доп. материалы)
   
  Navigation components

- Приведите пример - ui-элемента из категории Input Controls.

  Например: "Укажите дату рождения"

- Является ли командная строка частью GUI?
  
  Нет

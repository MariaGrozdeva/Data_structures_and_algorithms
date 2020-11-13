## Линейни структури:
**1.** Динамичен масив (вектор)  
**2.** Едносвързан списък  
**3.** Двусвързан списък  

## Реализация на *абстрактни* структури от данни:
**1.Стек**- Добавяне и премахване на елемент от една и съща страна.  
  
*1 вариант: pushBack && popBack*  
```diff
| |                    | pushBack | popBack |
| |--------------------|----------|---------|
|+| Вектор             |   O(1)   |   O(1)  |
|-| Едносвързан списък |   O(1)   |   O(n)  |
|-| Двусвързан списък  |   O(1)   |   O(1)  |
  ```
  *2 вариант: pushFront && popFront*  
  ```diff
| |                    | pushFront | popFront |
| |--------------------|-----------|-----------|
|-| Вектор             |   O(n)    |   O(n)    |
|+| Едносвързан списък |   O(1)    |   O(1)    |
|-| Двусвързан списък  |   O(1)    |   O(1)    |
```

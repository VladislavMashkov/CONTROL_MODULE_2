# Vladislav Mashkov
1. Реализуйте функцию `merge`, которая объединяет два отсортированных контейнера в один отсортированный. **Требования**: сложность по времени - `O(M + N)`. `M`, `N` размер контейнеров; сложностью по памяти - `O(1)`.
1. Дан неупорядочный массив целых чисел от `1` до `N`.
    1. Из этого массива удалено одно число `a`. Реализуйте функцию, которая возвращает это число `a` с минимальной сложностью по времени и с константной сложностью по памяти.
    1. Из этого массива удалено два числа `a` и `b`. Реализуйте функцию, которая возвращает эти числа с минимальной сложностью по времени и с константной сложностью по памяти.
1. Дан односвязный список целых чисел. Реализуйте функцию разворота этого списка с минимальной сложностью по времени и с константной сложностью по памяти.
```cpp
struct Node
{
   int data;
   Node * next;
};

// требуется реализовать функцию
Node * reverse(Node * head);
```

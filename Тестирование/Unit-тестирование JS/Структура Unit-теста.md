#### Arrange

Настройка состояние, которое находится за пределами компонента, то есть в него приходит. Определять состояние в других фазах не приветствуется.

Падение теста на этом этапе не нарушает его честность.



#### Act

Вызов необходимых методов для тестирования и дальнешей проверки результата. В некоторых случаях действия выносят в фазу `Arrange`, чтобы ввести компонент в определенное состояние и не нарушить его  `честность`

```
button.trigger('click');
const result = a.getDiscount();
...
```



#### Assert

Проверка результата

```
result === 20
```


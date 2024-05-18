# Angular interview

## Angular
1. Чем компонент отличается от директивы?
2. Что такое impure pipe? 
3. Зачем нужен декоратор ViewChild?
4. Что такое HTTP Interceptors?
5. Доводилось ли писать свои валидаторы реактивных форм?
6. В чем преимущество от использования asyncPipe? Приходилось ли использовать?

## Typescript
1. Что такое generic type? Доводилось ли писать?
2. Что такое перегрузка функций? Зачем нужна?
3. В чем отличие type от interface?
4. В чем назначение ключевого слова infer?
5. Чем интерфейс отличается от абстрактного класса?

## RxJS
1. Что такое Subject и BehaviourSubject? В чем отличие?
2. Зачем нужна отписка от Observable? Всегда ли нужно отписываться?
3. В чем отличие forkJoin от combineLatest?
4. Что будет выведено в консоль в результате выполнения кода?
````
timer(0, 1000)
  .pipe(
    distinctUntilChanged(),
    filter((value) => value < 5),
    tap((value) => value + 1),
    take(1)
  )
  .subscribe((result) => {
    console.log(result);
  });
````
5. Что будет выведено в консоль и в каком порядке?
````
setTimeout(() => console.log(1));
Promise.resolve(2).then(console.log);
of(3).subscribe(console.log);
````
6. Что такое race condition? Как его избежать?

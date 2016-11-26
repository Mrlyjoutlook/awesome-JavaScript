#Immutable 中文文档
整理日常使用immutable api的使用方法，ES6标准

## 目录

- [fromJS()](#fromJS())
- [is()](#is())
- [List,Map](#List,Map)
- [Construction](#construction)

## fromJS()
深度的将原生JS对象和数组转变成immutable的`Map`和`List`类型。与单纯的使用List()...转变还是有区别。

```
fromJS({aa:1}) or fromJS([1,2])
```

## is()

## List,Map

### Construction
List() 将原生JS数组转变成immutable的`List`类型

```
List([])
```
Map() 将原生JS对象转变变成immutable的`Map`类型

```
Map({})
```


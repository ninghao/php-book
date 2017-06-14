# 类

在 PHP 里，定义一个类用的是 class 关键词。

创建一个类，名字叫 Dog：

```php
class Dog {

}
```

## 属性

类里的值就是属性（property）。

在类里添加一个公开的属性，属性的名字是 $name：

```php
class Dog {
  public $name; 
}
```

## 方法

类里面的函数就叫方法（method）。

在类里添加一个公开的方法，方法的名字叫 talk\(\)：

```php
class Dog {
  public function talk() {
    echo '汪汪 ~';
  }
}
```

## 对象

基于类可以创建一个对象，可以使用 `new` 关键词，后面加上类的名字。

创建 Dog 类，创建一个对象，像这样：

```php
$dog = new Dog();
```

设置对象里的属性的值，使用 `->` 符号，像这样：

```php
$dog->name = '小白';
```

> 小白是《蜡笔小新》里的小狗。

访问对象里的属性：

```php
$dog->name;
```

使用对象里的方法：

```php
$dog->talk();
```




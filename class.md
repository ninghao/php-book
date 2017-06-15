# 类

在 PHP 里，定义一个类用的是 class 关键词。

**例：**

创建一个类，名字叫 Dog：

```php
class Dog {

}
```

## 属性

类里的值就是属性（property）。

**例：**

在类里添加一个公开的属性，属性的名字是 $name：

```php
class Dog {
  public $name; 
}
```

## 方法

类里面的函数就叫方法（method）。

**例：**

在类里添加一个公开的方法，方法的名字叫 talk\(\)：

```php
class Dog {
  public function talk() {
    return '汪汪 ~';
  }
}
```




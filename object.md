# 对象

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

## $this

在类里，$this 表示当前对象。

添加一个方法叫 `getName()`，在这个方法里用一下 `$this`：

```php
class Dog {
  public $name;
  public function getName() {
    return $this->name;
  }
}
```




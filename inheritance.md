# 继承

让一个类从另一个类那里继承点什么，用的是 extends 。

## 练习

有个类叫 Article，表示文章内容：

```php
class Article {
  public $title;
}
```

让 Movie，电影去继承 Article：

```php
class Movie extends Article {

}
```

测试：

```php
$movie = new Movie();
var_dump($movie);
```

在输出的东西里，你会发现 Movie 对象里面会包含 title 属性，即使我们没在 Movie 里定义 title ，但是 Movie 继承了 Article，所以 Movie 对象里会包含在 Article 里定义的东西。


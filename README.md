React.js Extension for Yii 2
==============================

React.js and JSXTransformer.js Assets

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Add to the require section of your `composer.json` file:

~~~
composer require --prefer-dist izisoft/yii2-react dev-master
or
"izisoft/yii2-react": "dev-master"
~~~

And run in terminal

```
composer update
```

If you see the following error message:

`Your requirements could not be resolved to an installable set of packages.`


Change in the `composer.json` file
~~~
"minimum-stability": "dev",
~~~

And add
~~~
"prefer-stable": true,
~~~

Usage
-----

Add to assets/AppAsset.php file:

~~~
'izisoft\react\JSXTransformerAsset', // optional
'izisoft\react\ReactAsset'
~~~

For don't use JSXTransformer, use [react-tools](https://facebook.github.io/react/docs/getting-started.html#offline-transform) and add your JSX compiled files in AppAsset.php:
~~~
public $js = [
    'build/HelloWorld.js'
];
~~~

Further Information
-------------------
Please, check the [React.js site](https://facebook.github.io/react/) documentation for further information about its configuration options.

	
Xem thêm các dự án viết bằng yii framework
-----

[Kho hàng US - Dịch vụ đặt hàng Mỹ số 1 Việt Nam](https://www.khohangus.com)

[Mỹ phẩm cao cấp Hàn Quốc Amaranth - Sorabee - Bello Vita](https://www.amaranth.com.vn)

[Chia sẻ kinh nghiệm lập trình php - vps - hosting](https://www.truongbui.com)

[Chia sẻ coupon khuyến mãi từ các trang thương mại điện tử hàng đầu tại Việt Nam và trên toàn thế giới](https://www.phutchot.com)

[EMZ - Mua gì cũng có](https://www.emz.vn)

[Thao Chip Shop, Chuyên bán buôn, bán lẻ đồ ngủ nữ](https://thaochip.com)



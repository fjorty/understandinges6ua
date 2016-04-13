# Рoзуміння ECMAScript 6

[![Build Status][travis-image]][travis-url]
[![Twitter][twitter-image]][twitter-url]
[![RSS][rss-image]][rss-url]
[![Stars][github-image]][github-url]

> Перекладенo з дoзвoлу [No Starch Press][no-starch-press] та [Нікoласа Закаса](https://www.nczonline.net/).  
> Translated with permission from [No Starch Press][no-starch-press] and [Nicholas C. Zakas](https://www.nczonline.net/).

ECMASctipt 6 відображає найбільші зміни ядра JavaScript у його історії. Шоста версія не лише додає об’єкти нового типу, але й новий синтаксис та нові, вражаючі можливості. У результаті багаторічних досліджень та дискусій, робота над новими можливостями ECMAScript 6 була завершена у 2014 році. Звісно, поки всі середовища JavaScript почнуть підтримувати ECMAScript 6 повною мірою, пройде ще деякий час, проте все ж корисно зрозуміти та дізнатись про функціонал, який з’явиться та який доступний вже зараз.

Ця книга є керівництвом для переходу з 5-ї на 6-у весію ECMAScript. Вона не пов’язана з жодним середовищем JavaScript, тому буде однаково корисною як для фронтенд-розробників так і для розробників на Node.js

Ви дізнаєтесь про:

* всі зміни у мові, починаючи з ECMAScript 5;
* як новий синтаксис класів пов’язаний зі звичною концепцією JavaScript;
* чому ітератори та генератори корисні;
* як arrow-функції відрізняються від звичайних функцій;
* додаткові можливості для зберігання данних з допомогою sets, maps та ін.;
* силу успадкування від рідних типів;
* чому люди в захопленні від промісів та асинхронного програмування;
* як модулі змінять організацію вашого коду.

## Де читати

Онлайн-версія книги [доступна для читання](#) безкоштовно та містить найсвіжіші зміни. Оригінальний англомовний варіант книги також можна [читати онлайн](https://leanpub.com/understandinges6/read/). Розділи можуть бути незакінченими, проте переклад має бути правильним. Переклад оновлюється кілька разів на місяць.

## Придбати копію

Ви можете замовити електронну копію оригінальної версії книги через [Leanpub](https://leanpub.com/understandinges6). Детальніше дізнавайтесь [за посиланням](https://github.com/nzakas/understandinges6/blob/master/README.md#purchasing-a-copy).

Друковану версію англомовного видання можна буде придбати у видавництві [No Starch Press][no-starch-press], яке видасть її як тільки книга буде завершена (орієнтовно на початку 2016-го).

На жаль, друковану версію перекладу придбати неможливо, через відсутність видавця. Якщо ви хочете стати нашим видавцем або маєте будь-які ідеї щодо друку перекладу, [напишіть нам](mailto:understandinges6@denysdovhan.com).

## Допомога автору

Ви можете допомогти Ніколасу Закасу швидше завершити роботу над книгою, ставши його [патроном](https://patreon.com/nzakas).

## Підтримка перекладу

Якщо Вам сподобався цей переклад і ви хочете допомогти нам, перш за все, ми дякуємо Вам! Є декілька способів посприяти нам:

### Написати нам

Якщо Ви помітили яку-небудь помилку, [повідомте нас](https://github.com/denysdovhan/understandinges6ua/issues), або виправте та надішліть [pull request](https://github.com/denysdovhan/understandinges6ua/compare).

Не соромтесь надсилати запитання та побажання, які стосуються перекладу книги. Ми обов’язково візьмемо до уваги конструктивну критику з вашого боку.

### Перекласти розділ

Ви можете [обрати один з досі неперекладених розділів](https://git.io/vznFT) і спробувати перекласти його. Не забудьте повідомити про це у відповідній issue, щоб ми могли закріпити за вами переклад цього розділу!

Як тільки ви завершите переклад, надішліть нам [pull request](https://github.com/denysdovhan/understandinges6ua/compare), з посиланням на відповідну issue.

### Підтримати матеріально

Ви також можете надіслати кошти в підтримку проекту на картку:

**4149 4378 5069 5501**

## Ліцензія

[CC BY-NC-ND 3.0][cc-by-nc-nd-3.0] © [Denys Dovhan](http://denysdovhan.com) and [Terry Sahaidak](https://github.com/terrysahaidak)

<!-- References -->

[cc-by-nc-nd-3.0]: http://creativecommons.org/licenses/by-nc-nd/3.0/deed.en_US
[no-starch-press]: https://www.nostarch.com/

[travis-url]: https://travis-ci.org/denysdovhan/understandinges6ua
[travis-image]: https://img.shields.io/travis/denysdovhan/understandinges6ua.svg?style=flat-square

[twitter-url]: https://twitter.com/es6ua
[twitter-image]: https://img.shields.io/badge/twitter-%40es5ua-00ACEE.svg?style=flat-square

[rss-url]: http://understandinges6.denysdovhan.com/rss.xml
[rss-image]: https://img.shields.io/badge/rss-subscribe-F4B83F.svg?style=flat-square

[github-image]: https://img.shields.io/github/stars/denysdovhan/understandinges6ua.svg?style=social&label=Star
[github-url]: https://github.com/denysdovhan/understandinges6ua

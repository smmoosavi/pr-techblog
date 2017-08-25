---
layout: post
title: اجرای jekyll با استفاده از docker
pdate: 1396-6-3
author: seyyed
tags: jekyll docker
---

بعد از اینکه بلاگ پول‌ریکوست رو خوندم گفتم بد نیست چند مطلب توش بنویسم، ولی دیدم که متاسفانه پای jekyll وسطه، و این یعنی پای ruby وسطه. برای این‌که از دست روبی فرار کنم و از دست بند و بساطش راحت بشم به docker پناه بردم.

بعد از یه جست‌جوی کوچیک دید که تیم jekyll خودشون داکرش رو هم دادن. دست به کار شدم و یه فایل docker-compose.yml به پروژه اضافه کردم، بعد از برخورد با چند تا خطا فایل GemFile رو به پروژه اضافه کردم و الان همه چی رو به راه هستش. برای اطلاعات بیشتر هم می‌تونید به 
[گیت‌هاب][github]
 داکر jekyll مراجعه کنید

از این به بعد برای نوشتن در [pullrequest.ir] دیگه لازم نیست روبی و jekyll رو نصب کنید. فقط کافیه وارد فولدر بلاگ شید و بنویسید

```
docker-compose up
```

ــپی‌نوشتــ

اگر تا به حال داکر کامپوز رو نصب نکردید از این 
[پیوند][docker-compose]
کمک بگیرید

[pullrequest.ir]: http://pullrequest.ir/
[github]: https://github.com/jekyll/docker
[docker-compose]: https://docs.docker.com/compose/install/
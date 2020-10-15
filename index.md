---
layout: page
title: ترم گمشده شما در علوم کامپیوتر
---

کلاس‌ها به شما همه‌چیز درباره علوم کامپیوتر یاد می‌دهند. از سیستم‌عامل گرفته تا یادگیری ماشین.
اما یک موضوع هست که به سختی آموزش داده می‌شود و در عوض به دانشجو سپرده می‌شود تا خودش یاد بگیرد:
چیرگی به ابزار‌ها. ما به شما یاد خواهیم داد چگونه با خط فرمان کار کنید، از یک ویرایشگر متنی قوی استفاده کنید،
از قابلیت‌های زیبای سامانه کنترل سیستم‌ها استفاده کنید و خیلی بیشتر.

دانشجو‌ها صدها ساعت از این ابزار‌ها در مسیر تحصیلی (و هزاران ساعت در مسیر شغلی) خود، صرف کار با این ابزار‌ها می‌کنند. پس کاملا منطقی‌ست که هر چه بیشتر با این ابزار‌ها انس پیدا کرد. تبحر پیدا کردن در این ابزار‌ها نه تنها به شما کمک می‌کند زمان کمتری را صرف خم‌کردن روش کارتان برای مقصودتان کنید، بلکه باعث می‌شود بتوانید مشکلاتی را حل کنید که قبلا غیر ممکن بنظر می‌رسیدند.

درباره [انگیزه پشت این کلاس](/about/) بخوانید.

{% comment %}
# ثبت‌نام

Sign up for the IAP 2020 class by filling out this [registration form](https://forms.gle/TD1KnwCSV52qexVt9).
{% endcomment %}

# فهرست

{% comment %}
**Lecture**: 35-225, 2pm--3pm<br>
**Office hours**: 32-G9 lounge, 3pm--4pm (every day, right after lecture)
{% endcomment %}

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>
همین‌طور می‌توانید همین مباحث را به‌صورت ویدئو [در یوتوب](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J) (به زبان انگلیسی) مشاهده کنید.

# درباره این کلاس

 این کلاس توسط گروهی از اساتید دانشگاه MIT تنظیم و تهیه شده. اگر سوالی داشتید به آنها می‌توانید [ایمیل](mailto:missing-semester@mit.edu) بزنید. ما نیز با ترجمه این دوره، سعی در انتشار این موضوعات برای فارسی‌زبانان داریم.

# فراتر

این دوره کمی فراتر از  این وبگاه است و در جاهای مختلفی به اشتراک گذاشته شده. برای پیدا کردن پست‌ها و گفت‌وگو‌های بیشتر درباره این دوره، می‌توانید به مسیرهای زیر سر بزنید:

 - [Hacker News](https://news.ycombinator.com/item?id=22226380)
 - [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
 - [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
 - [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
 - [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
 - [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

# به زبان‌های دیگر

- [Chinese (Simplified)](https://missing-semester-cn.github.io/)
- [Chinese (Traditional)](https://missing-semester-zh-hant.github.io/)
- [Korean](https://missing-semester-kr.github.io/)
- [Portuguese](https://missing-semester-pt.github.io/)
- [Serbian](https://netboxify.com/missing-semester/)
- [Spanish](https://missing-semester-esp.github.io/)
- [Turkish](https://missing-semester-tr.github.io/)
- [Vietnamese](https://missing-semester-vn.github.io/)

هنگام این دوره یادداشت‌برداری کرده‌اید؟ می‌توانید آن‌را [اینجا](https://github.com/cs-fum/cs-fum.github.io/pulls) بگذارید تا ما به لیست‌مان اضافه کنیم

## سپاسگزاری‌ها

از تمام کسانی که مارا در ترجمه این دوره یاری دادند/می‌دهند/خواهند داد.

---

<div class="small center">
<p><a href="https://github.com/cs-fum/cs-fum.github.io">کد منبع</a>.</p>
<p>تحت مجوز کریتیو کامنز اتریبیوشن ۴.۰ اینترنشنال</p>
<p><a href="/license/">اینجا</a> را برای چگونگی مشارکت و همکاری بخوانید</p>
</div>

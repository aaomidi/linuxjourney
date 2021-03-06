# Disk Usage

## محتویات درس

چند ابزار برای دیدن عمل‌کرد دیسک سخت وجود دارد.

```
pete@icebox:~$ df -h
Filesystem     1K-blocks    Used Available Use% Mounted on
/dev/sda1       6.2G  2.3G  3.6G  40% /
```

دستور df به شما در خصوص فایل‌سیستم‌های سوار شده اطلاعاتی را نمایش می‌دهد. فلگ ‎-h خروجی را برای انسان (human) دوستانه‌تر می‌کند تا راحت‌تر اطلاعات را بخوانید. همچنین می‌توانید در خصوص دستگاه ذخیره‌ساز و اینکه چقدر فضای استفاده‌شده یا خالی دارد از طریق این دستور اطلاعات مفیدی کسب کنید.

فرض کنیم که دیسک شما پُر شده و می‌خواهید بدانید که کدام فایل‌ها و پوشه‌ها این فضا را اشغال کرده‌اند. برای این کار می‌توانید از فرمان du استفاه کنید.

```$ du -h```

این فرمان، میزان فضای مصرف شده در دیسک را از مسیر جاری به شما نشان می‌دهد. با
دستور **‎du -h /‎** هم می‌توانید نگاهی به دایرکتوری روت بیندازید، ولی خب احتمالاً اوضاع کمی شلوغ پلوغ خواهد بود.

هر دوی این دستورها ساختار دستور یکسانی دارند و سخت است که به یاد بیاورید کدام یک را کِی استفاده کنید. به هر حال زمانی که می‌خواهید ببیند چقدر از فضای دیسک خالی است (Disk Free) از **df** و زمانی که خواستید ببینید چقدر از دیسک استفاده شده (Disk Usage) از **du** استفاده کنید.

## تمرین

با استفاده از دو دستور du و df نگاهی به میزان فضای خالی و استفاده شده‌ی دیسک بیندازید.

## سؤال آزمون

از چه دستوری برای مشاهده‌ی میزان فضای خالی دیسک استفاده می‌کنید؟

## پاسخ آزمون

df

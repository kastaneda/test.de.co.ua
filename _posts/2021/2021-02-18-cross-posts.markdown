---
title: Cross-posts
date: 2021-02-18 07:32:00 +02:00
---

Мій [попередній пост][1] я синхронізував «руками». Технічно кажучи, це дві публікації (дві звичайні веб-сторінки) на моїх сайтах, плюс пост у моєму Dreamwidth, плюс пост у новій для мене соцмережі Diaspora.

Звісно, це було для експерименту. Та я планую зробити нормальний сабж.

Щоб постити в Dreamwidth, є [відповідне API][2]. Треба конвертувати контент з Markdown до фрагмента HTML (як це робить Pandoc за замовчанням), зробити  новий пост з `opt_preformatted: true`, отримати `itemid` та `url` у відповідь та зберігати його у front matter.

Треба пошукати, як автоматично робити пости до Diaspora. Принаймні, конвертувати нічого не треба.

Upd: звісно ж, і для Diaspora* є [відповідне API][3].

[1]: https://test.de.co.ua/2021/02/18/chromium-end.html
[2]: https://web.archive.org/web/20170626064901/http://www.livejournal.com/doc/server/ljp.csp.flat.postevent.html
[3]: https://diaspora.github.io/api-documentation/routes/posts.html#publish-a-post

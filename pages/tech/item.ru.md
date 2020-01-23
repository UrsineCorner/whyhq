---
title: 'Техническая страница'
media_order: 'fun.jpg,droplets-150.png,hg-150.png,uc.jpeg,lb.jpeg'
date: '13-11-2019 00:27'
taxonomy:
    category:
        - internal
hide_git_sync_repo_link: false
body_classes: header-light
routes:
    default: /special/collection
hero_classes: 'text-light title-h1h2 overlay-dark-gradient hero-large parallax'
hero_image: fun.jpg
header_image_alt_text: 'Просто кот'
blog_url: /blog
show_sidebar: false
show_breadcrumbs: false
show_pagination: false
hide_from_post_list: false
feed:
    limit: 10
twitterenable: false
twittercardoptions: summary
articleenabled: true
article:
    datePublished: '13-11-2019 00:32'
    dateModified: '10-01-2020 19:42'
    image_url: /tech/fun.jpg
    author: 'Lazy Badger'
    publisher_logo_url: /tech/uc.jpeg
    publisher_name: UrsineCorner
orgaenabled: true
orga:
    ratingValue: 3
orgaratingenabled: false
eventenabled: false
personenabled: false
facebookenable: false
subtitle: 'Всяческая мелочь'
hide_page_title: '0'
content:
    items: '@root.descendants'
    limit: '10'
    order:
        by: date
        dir: asc
    pagination: '1'
    url_taxonomy_filters: '1'
bricklayer_layout: '1'
display_post_summary:
    enabled: '0'
display_child_page_titles: '0'
display_content_titles: '1'
---

Обычная техническая страница для сбора локальных данных, которые нужны много раз.

Дублирую сюда, так как легкий выбор есть только из файлов к страницам.

{{ page.collection.first().date|date('Y') }}

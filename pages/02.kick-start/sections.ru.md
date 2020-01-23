---
title: 'Mercurial: взлет ракетой'
date: '04-11-2019 20:23'
hide_git_sync_repo_link: false
hide_page_title: true
content:
    items: '@self.children'
    order:
        by: folder
        dir: asc
    taxonomy:
        filter:
            - basic
            - advanced
hide_next_prev_page_buttons: false
googledesc: 'Этот раздел — перевод Mercurial Kick Start, его адаптация/локализация и обновление под Mercurial 2019 года.'
twitterenable: true
twittercardoptions: summary
twittershareimg: /tech/hg-150.png
twittertitle: ' Mercurial: взлет ракетой'
twitterdescription: 'Этот раздел — перевод Mercurial Kick Start, его адаптация/локализация и обновление под Mercurial 2019 года.'
articleenabled: false
article:
    headline: 'Mercurial: взлет ракетой'
    datePublished: '04-11-2019 20:23'
    dateModified: '19-12-2019 16:14'
    description: 'Этот раздел — перевод Mercurial Kick Start, его адаптация/локализация и обновление под Mercurial 2019 года.'
    image_url: /tech/hg-150.png
    author: 'Lazy Badger'
    publisher_logo_url: /tech/uc.jpeg
    publisher_name: UrsineCorner
orgaenabled: true
orga:
    name: UrsineCorner
    description: 'Generator of custom IT-solutions'
    streetaddress: 'Dobrolyubova 16/2'
    city: Ekaterinburg
    state: Russia
    areaserved:
        -
            area: Russia
    phone: '+7 953 822-88-81'
    url: 'https://ursinecorner.ru'
    ratingValue: 3
    foundingDate: '2011'
    email: mayor@ursinecorner.ru
    founders:
        -
            name: 'Lazy Badger'
        -
            name: E-Lena
orgaratingenabled: false
eventenabled: false
personenabled: true
addperson:
    -
        person_name: 'Lazy Badger'
        person_jobTitle: CIO
        person_address_addressLocality: Ekaterinburg
        person_address_addressRegion: Ural
facebookenable: true
facebooktitle: ' Mercurial: взлет ракетой'
facebookdesc: 'Этот раздел — перевод Mercurial Kick Start, его адаптация/локализация и обновление под Mercurial 2019 года.'
facebookauthor: 'https://www.facebook.com/alexander.leschinsky.3'
facebookimg: /tech/hg-150.png
---

[div class="sections-page-title"]
## Курс молодого бойца в Mercurial
[/div]

Этот раздел — перевод с [английского источника](http://mercurial.aragost.com/kick-start/en/ "Mercurial Kick Start на сайте aragost Trifork"), его адаптация/локализация и обновление под реалии Mercurial 2019 года, закономерно изменившиеся со времени создания оригинального документа в 2012 году.

Локализация документа состоит в том, что вместо перевода и использования имен участников фиктивной команды разработчиков Alice, Bob, Carla (A/B/C, для недогадливых) "как есть", использованы соотвествующие русские имена по такому же принципу.

Адаптация — немного более серьезное изменение, основанное на личном убеждении и практике, что начальный уровень Mercurial можно и нужно проходить не в консоли, а сразу в GUI, так как TortoiseHG не имеет таких серьезных ограничений по возможностям полноценной работы и не прячет сложности системы за простым интерфейсом, как его "родственники": TortoiseSVN и TortoiseGit. Кроме этого, он реально кроссплатформенный, работает везде, и умение его использовать, полученное на, к примеру, Windows, не превратится в тыкву при переходе на работу с MacOS|Linux. В соответствии с этим убеждением все (кроме тех, где консоль действительно необходима) примеры с консольными командами заменены на скриншоты из TortoiseHG 5 версии.
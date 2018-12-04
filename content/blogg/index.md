---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        title: Senaste inläggen
        data:
            meta:
                type: copy
                view: blog-list

---
Emils bild blogg
===========================

Här kommer jag lägga upp dagens bild, verkar dock inte gå nått vidare med tanke på att jag har lagt upp tre bilder de senaste två månaderna. Men snart så... Ska bara...

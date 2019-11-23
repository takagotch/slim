### slim
---
http://slim-lang.com/

https://github.com/slim-template/slim

https://github.com/slim-template/slim/blob/master/README.jp.md

```.slim
doctype html
html
  head
    title Slim Examples
    meta name="keywords" content="template language"
    meta name="author" content=author
    javascript:
      alert('Slim supports embedded javascript!')
      
  body
    h1 Markup examples
    
    #content
      p This example shows you what a basic Slim file looks like.
      
      == yield
      
      - unless items.empty?
        table
         - items.each do |item|
           tr 
             td.name = item.name
             td.price = item.price
             
      - else
        p
         | No items found. Please add some inventory.
           Thank you!
           
    div id="footer"
      = render 'footer'
      | Copyright C #{year} #{author}
```

```
```

```
```



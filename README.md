# assingment2-schreiner
# Avery Schreiner
## Basketball
I like **basketball** because I am good at it.
I enjoy the **team aspect** of it, as you don't have to be 
a master of all things in basketball, but your team
can be composed of individuals who have unique skills.
<hr>

## Ordered List
LA Lakers
1. LeBron James
2. Anthony Davis
3. Russell Westbrook

## Unordered List
Other teams that would be good to watch:
* Boston Celtics
* Milwaukee Bucks
* Memphis Grizzlies

**[to AboutMe.md](AboutMe.md)**
<hr>

## Tables
Tables are useful for separating information. Here is a table of the countries I recommend you visit!
| Name | Why go here? | Days |
| --- | --- | ---: |
| England | Tea, Big Ben, Palace Guard | 7 |
| France | Wine, Eiffel Tower, Mopeds | 12 |
| Italy | Pasta, Amazing History, Coastlines | 14 |
| USA | Nice cities, beaches, mountains, all! | 15 |
<hr>

## Quotes
> "I have a dream that my four little children will one day live in a nation where they will not be judged by the color of their skin but by the content of their character." *- Martin Luther King Jr.*

> "Man cannot remake himself without suffering, for he is both the marble and the sculptor" *-Alexis Carrel*
<hr>

## Code Fencing

> Serving your XHTML with the correct MIME type [to StackOverflow](https://stackoverflow.com/questions/6009240/serving-your-xhtml-with-the-correct-mime-type)


```
RewriteEngine On
RewriteCond %{HTTP_ACCEPT} application/xhtml\+xml
RewriteCond %{HTTP_ACCEPT} !application/xhtml\+xml\s*;\s*q=0
RewriteCond %{REQUEST_URI} \.html$
RewriteCond %{THE_REQUEST} HTTP/1\.1
RewriteRule .* - "[T=application/xhtml+xml; charset=ISO-8859-1]"
```

[snippet source](https://css-tricks.com/snippets/htaccess/force-correct-content-type-for-xhtml-documents/)
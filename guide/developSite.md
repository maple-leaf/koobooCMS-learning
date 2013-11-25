Develop your site
----------------------------
Check this development part at 
[Official Guide](http://www.kooboo.com/docs/Kooboo-CMS/kooboo_development)

##Some word explanation :##
### Layout:
Page1:

    <!DOCTYPE html>
    <html>
        <head>
            <meta http-equiv="content-type" content="text/html; charset=utf-8" />
            <title>Page Title</title>
        </head>
        <body>
            <div class="main">
                <ul><li> different part</li></ul>
            </div>
            <div class="footer">footer</div>
        </body>
    </html>

Page2: 

    <!DOCTYPE html>
    <html>
        <head>
            <meta http-equiv="content-type" content="text/html; charset=utf-8" />
            <title>Page Title</title>
        </head>
        <body>
            <div class="main">
                <div> different part</div>
            </div>
            <div class="footer">footer</div>
        </body>
    </html>

This two page are same except ``main`` section. If we remove html within main section , we get same html structure as below:

    <!DOCTYPE html>
    <html>
        <head>
            <meta http-equiv="content-type" content="text/html; charset=utf-8" />
            <title>Page Title</title>
        </head>
        <body>
            <div class="main">
                
            </div>
            <div class="footer">footer</div>
        </body>
    </html>

This is ``Layout`` for these two pages.

### View
We can insert ``<ul><li> different part</li></ul>`` to layout to get complete page1, so we call ``<ul><li> different part</li></ul>`` is  a ``View`` for page1.
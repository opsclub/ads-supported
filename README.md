# ads-supported
Convince users to disable ad-block when browsing your site

## Setup (only proceed if you know what you're doing!):
1. Change your CDN or assets hostname to point to ads.yourdomain.com or ads.supported.yourdomain.com (i.e cdn.sendasgift.com would become ads.sendasgift.com or ads.supported.sendasgift.com)
2. Add the following to your main stylesheet:
```css
.adblock {display:none}
```
3. Wait until the new hostname populates and you can access your images, javascripts and stylesheets through the new hostname (i.e http://ads.supported.sendasgift.com/css/style.css is accessible and has the new css rule)
4. Add an anti-ad-block message of your choosing to any of your templates:
```html
<div class="adblock" style="color:red">
  Your ad block may be preventing access to our website. Please disable it :)
</div>
```
5. Change your application to point all assets to the new hostname
6. Upload and see the changes

## Sample websites (send me yours and I'll add it here):
* http://sendasgift.com

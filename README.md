# Zocial CSS social buttons

I basically rewrote this entire set so they are full vector buttons, meaning:

- @font-face icons
- custom font file for all social icons
- em sizing based on button font-size
- support for about 44 different services
- buttons and icons supported
- no raster images (sweet)
- works splendidly on any browser supporting @font-face
- CSS3 degrades gracefully in <IE8 etc.

How to use these buttons:

1. You only need zocial.css and the font files.
2. The markup is really straightforward, for example:

<button class="zocial facebook"><span>Button text here</span></button>

3. You can use any parent element you like (button, p, a, whatever), just remember the nested span (and this *must* be a span element)
4. Include the class ".zocial" on the parent element
5. Specify the type of button by including its name "facebook", "google", "dropbox" etc.
6. Include whatever button text you like.
7. Done! Happy days.

## More info
Check out [zocial.smcllns.com](http://zocial.smcllns.com) for demo and code examples.

Problems or questions to [@smcllns](http://twitter.com/smcllns)
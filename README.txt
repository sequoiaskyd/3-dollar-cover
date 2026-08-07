$3 COVER  ::  WEBSITE
=====================

WHAT YOU HAVE
-------------
index.html      -> the whole website (one file)
assets/         -> put your images in here (see below)
README.txt      -> this file

To view it: double-click index.html and it opens in your web browser.


STEP 1: ARTWORK  (mostly done already)
--------------------------------------
Two of the three artwork slots are already filled in, so there is nothing
you need to do for them:

  DONE  assets/brand.webp  -> the red "$3 COVER" wordmark, top-left of
                              every page
  DONE  assets/logo.webp   -> the torn "Admit One" ticket, shown large in
                              the hero at the top of the page

STILL MISSING (optional):

  assets/ticket.png  -> a ticket image shown next to the "Shows" heading

If that file is absent the site simply hides that image and everything
else looks normal, so you can leave it alone indefinitely.

To replace either of the finished images, drop in a new file with the
same name. Keep the .webp extension: WebP is what makes the transparent
background work at a small file size. If you only have a .png or .jpg,
don't just rename it, since that produces a broken image. Ask for it to
be converted.


STEP 2: FILL IN THE PLACEHOLDERS
-------------------------------
Open index.html in any text editor and search for "EDIT:". Every spot you
should personalize is marked. The main ones:

  * Your city/state       -> search for  [Your City, State]  (footer)
  * Listen links          -> Spotify / Apple / YouTube / Bandcamp URLs
  * Videos                -> paste YouTube/Vimeo embeds or links
  * Shows                 -> real dates, venues, and ticket links
  * Gallery               -> swap the "Photo 01" tiles for real photos
  * Social links (footer) -> Instagram / YouTube / Spotify

Anything you don't have yet can be left as-is; it's clearly marked.


BOOKING EMAIL
-------------
The "Book Us" button and contact section email:  threedollarcover@gmail.com
(Change it in index.html if you ever want a different address. Search
for that email and replace every copy.)


PUTTING IT ONLINE
-----------------
It is already online, at:

  https://threedollarcover.com

So you do not need to host it anywhere. Edits you make here only reach
the live site once someone copies the files up to the server, which is
not automatic.

Typing "3dollarcover.com" (without the "three") also lands on the site.
That shortcut only works with http, not https.

If you ever DO need to move it somewhere else, it is a plain static
website and will run on almost any host (Netlify, GitHub Pages,
Cloudflare Pages, or any web host that accepts uploaded files). Upload
the WHOLE folder together: index.html plus the assets folder.

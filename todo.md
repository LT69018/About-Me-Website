- [ ] Populate about me page + make a folder for images (i.e. my headshot, a )
    - add resume, linkedIN, maybe twitter
- [ ] *find a way to have the header appear on each page. Is there a way to load/inject html from a **common header**.html?*
    - [X] Use Bootstrap to create a header.
    https://getbootstrap.com/docs/5.3/examples/headers/#
    - [ ] Probably use JS to populate the same header across multiple pages. So I don't have to keep copy and pasting it between files!

- [ ] Format: 
    - [ ] navbar active link (Want light purple with white text instead of completely white and black)
    - [ ] main container: want gap between the h1 and the navbar.
- [ ] Add preview image to ReadME.md

Resolved:
- [X] index.html: Fix formatting of body container. (wondering why it doesn't look the same as the about-me.html)
    - Figured it out, I accidentally closed the div container class before I put the header and paragraph in it.
- [X] Link the about me page back to the main html (index.html)
    - as of 2/9 this is happening by just copying and pasting a `<nav>` between html pages.
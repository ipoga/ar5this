## ar5this - A bookmarklet to turn your current arXiv reading into an ar5iv (HTML5 version) article

This bookmarklet simplifies converting arXiv articles into ar5iv (see https://ar5iv.org) articles, which are responsive HTML5 versions, much easier to read on mobile.

The bookmarklet is not related to the ar5iv page - all credit goes to them for powering this, the bookmarklet is ONLY a tiny shortcut.

### How to use

To use the bookmarklet, drag the link below to your bookmark bar. Once synchronized with your mobile browser, you can also use the bookmarklet by typing the name of it in the address bar of the page you want to convert to ar5iv.

This is the bookmarklet: [ar5iv](javascript:(function() {loc=window.location.toString();if(loc.includes('arxiv')){window.location=loc.replace('arxiv','ar5iv');}})();)

And for transparency, this is what it does:

```
javascript:(
  function() {
    loc=window.location.toString();
    if(loc.includes('arxiv')){
      window.location=loc.replace('arxiv','ar5iv');
    }
  }
)();
```

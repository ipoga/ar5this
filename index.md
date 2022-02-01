## ar5this

- A bookmarklet to turn your current arXiv reading into an ar5iv (HTML5 version) article

To use the bookmarklet, drag the link below to your bookmark bar. Once synchronized with your mobile browser, you can also use the bookmarklet by typing the name of it in the address bar of the page you want to convert to ar5iv.

[ar5iv](javascript:(function() {loc=window.location;if(loc.includes('arxiv')){window.location=loc.replace('arxiv','ar5iv');}})();)

```
function(){
  if (window.location.contains('://arxiv.org/')){
    window.location=loc.replace('://arxiv.org/','://ar5iv.org/');
  }
};
```

## ar5this

- A bookmarklet to turn your current arXiv reading into an ar5iv (HTML5 version) article

To use the bookmarklet, drag the link below to your bookmark bar. Once synchronized with your mobile browser, you can also use the bookmarklet by typing the name of it in the address bar of the page you want to convert to ar5iv.

[ar5this](javascript:(function(){if (window.location.contains('://arxiv.org/')){window.location=loc.replace('://arxiv.org/','://ar5iv.org/');}}).call(this);)

[ar5this](javascript:(function(){loc=window.location;if(loc.contains("arxiv"){alert(loc);}).call(this);)

[ar5this](javascript:if(document.location.contains(arxiv){alert(document.location);})

[test](javascript:(function(){loc=document.location;alert(loc);}).call(this);)

```
function(){
  if (window.location.contains('://arxiv.org/')){
    window.location=loc.replace('://arxiv.org/','://ar5iv.org/');
  }
};
```

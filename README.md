prototype-a11y
==============

accessibility functions for [Prototype Javascript Framework](http://www.prototypejs.org/)
------------------------------------------------------------

- Prototype.a11y.prepareBuffer(); 
- Prototype.a11y.updateBuffer(); updates virtual buffer for screenreader JAWS inspired by [juicystudio](http://juicystudio.com/article/improving-ajax-applications-for-jaws-users.php)
- Prototype.a11y.fixFocus(); inspired by [Paul Ratcliffe](http://www.communis.co.uk/blog/2009-06-02-skip-links-chrome-safari-and-added-wai-aria)

new Element.Methods

- Element.setTabIndex(index); crossbrowser implementation
- Element.removeTabIndex(); crossbrowser implementation
- Element.setFocus(miliseconds); delayed element.focus();

extended Element.Methods

- Element.hide(); added aria-hidden attribute and tabindex -1 
- Element.show(); added aria-hidden attribute and tabindex


Credits
-------

Created by [Sindre Wimberger](http://www.sindre.at).

# XQuery Axes

Within an XPath expression you can navigate your document using the following axes:

* `self::`
* `child::`
* `descendant::`
* `descendant-or-self::`
* `attribute::`
* `following::`
* `following-sibling::`
* `parent::`
* `ancestor::`
* `ancestor-or-self::`
* `preceding::`
* `preceding-sibling::`

Look at the following example, where an axis is used in a step

`doc("yourfile.xml")/rootNode/token/following::lemma`

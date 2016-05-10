# XQuery Axes

Within an XPath expression you can navigate your document using the following axes:

* `self::`
* `child::`
* `descendant::`
* `descendant-or-self::`
* `following::`
* `following-sibling::`
* `parent::`
* `ancestor::`
* `ancestor-or-self::`
* `preceding::`
* `preceding-sibling::`
* `attribute::`

Look at the syntax of the following example, where the axis is follwed by the name of an element:

`doc("yourfile.xml")/rootNode/token/following::lemma`

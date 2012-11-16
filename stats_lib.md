# Stats library

Generate statistics using SQL functions such as MIN, AVG, MAX, ...

I created this library because ActiveRecord #calculate method can only retrieve 1 calculation per query.

The end result looks like this:

![Alt text]( http://dl.dropbox.com/u/586025/Screenshots/mos_stats.png )

MOS means "Mean Opinion Score", this is a VoIP test metric.

## Class Diagram

![Alt text]( http://yuml.me/d8eac8c3 )

The main class is "Calculator" whose responsability is to retrieve Value Object stats through a Query and decorates them with a Presenter.

## Design Patterns

- [Composite Pattern](http://en.wikipedia.org/wiki/Composite_pattern)
- [Query Pattern]( http://blog.codeclimate.com/blog/2012/10/17/7-ways-to-decompose-fat-activerecord-models/ )
- [Value Object](http://martinfowler.com/bliki/ValueObject.html)
- [Presenter pattern](http://robots.thoughtbot.com/post/20964851591/decorators-compared-to-strategies-composites-and) 
- [Fluent Interface](http://www.martinfowler.com/bliki/FluentInterface.html)

## Sequence Diagram

How does it fit together?

The following sequence diagram was generated programatically with some special secret project of mine, relying heavily on meta programming.

[See the diagram full size]( http://www.websequencediagrams.com/cgi-bin/cdraw?lz=TW9zU3RhdCAtPiBDYWxjdWxhdG9yOiBpbmplY3RfZGVwZW5kZW5jaWVzCgAfDG9tcG9zaXRlACgMPDwAAiFvbgoAKBMAORlwYXNzX3RvX3N1YmNvbXBvbmVudHMKRXJiAGsZZm9yX2NhbGxlcgAKX3N0YXRzAIE0GQAXEgAHGXZhbHVlX29iamVjABcRUXVlcnk6IGFncmVnYXRlCgALBSAtPiBNb3NNaW5BdmdNYXgAHgdmaW5kABcKU3FsQQAvB01hcHBlcjogc3FsAGwbYnVpbGRfAIEBDACBJQ8APxNyZXRyaWV2ZV9hdHRyaWJ1dGVzX2ZvcgCBXg8AgSAJUHJlc2VudGUAhFoFaXRpYWxpemUAg0YIABIUbmFtAAMdbWluCgBMEiAtPiBEZWNpbWFsAGcLY29udmVydAoAChAAgQoYACkH&s=qsd )

![Alt text]( http://www.websequencediagrams.com/cgi-bin/cdraw?lz=TW9zU3RhdCAtPiBDYWxjdWxhdG9yOiBpbmplY3RfZGVwZW5kZW5jaWVzCgAfDG9tcG9zaXRlACgMPDwAAiFvbgoAKBMAORlwYXNzX3RvX3N1YmNvbXBvbmVudHMKRXJiAGsZZm9yX2NhbGxlcgAKX3N0YXRzAIE0GQAXEgAHGXZhbHVlX29iamVjABcRUXVlcnk6IGFncmVnYXRlCgALBSAtPiBNb3NNaW5BdmdNYXgAHgdmaW5kABcKU3FsQQAvB01hcHBlcjogc3FsAGwbYnVpbGRfAIEBDACBJQ8APxNyZXRyaWV2ZV9hdHRyaWJ1dGVzX2ZvcgCBXg8AgSAJUHJlc2VudGUAhFoFaXRpYWxpemUAg0YIABIUbmFtAAMdbWluCgBMEiAtPiBEZWNpbWFsAGcLY29udmVydAoAChAAgQoYACkH&s=qsd )

[Diagram source]( http://www.websequencediagrams.com/?lz=TW9zU3RhdCAtPiBDYWxjdWxhdG9yOiBpbmplY3RfZGVwZW5kZW5jaWVzCgAfDG9tcG9zaXRlACgMPDwAAiFvbgoAKBMAORlwYXNzX3RvX3N1YmNvbXBvbmVudHMKRXJiAGsZZm9yX2NhbGxlcgAKX3N0YXRzAIE0GQAXEgAHGXZhbHVlX29iamVjABcRUXVlcnk6IGFncmVnYXRlCgALBSAtPiBNb3NNaW5BdmdNYXgAHgdmaW5kABcKU3FsQQAvB01hcHBlcjogc3FsAGwbYnVpbGRfAIEBDACBJQ8APxNyZXRyaWV2ZV9hdHRyaWJ1dGVzX2ZvcgCBXg8AgSAJUHJlc2VudGUAhFoFaXRpYWxpemUAg0YIABIUbmFtAAMdbWluCgBMEiAtPiBEZWNpbWFsAGcLY29udmVydAoAChAAgQoYACkH&s=qsd )
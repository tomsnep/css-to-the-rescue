# css-to-the-rescue

Tom Snepvangers
500684506

=====================

[Exercises can be found here](http://tomsnep.github.io)


Aria:
http://w3c.github.io/aria-in-html/
http://html5doctor.com/using-aria-in-html/


attribute selectors: 


attribute rel
```
	<a href="" rel="next"> 
```
css:
```
	attr slector: [rel=next] {}
```
role:
```
	<footer role="contentinfo"><p>....</p></footer>
```
css: 
```
	[role=contentinfo] p{}
```

klikbare navigatie: 

maak de a in de li dislay: block;
```
	li a:hover {
		display: block;
	}
```

nieuwe width units: min-content & max-content
```
figure {
    max-width: 300px;
    max-width: min-content;
    margin: auto;
}

figure > img { max-width: inherit; }”
```

Vertical and horizontal centering:

```
body {
    display: flex;
    min-height: 100vh;
    margin: 0;
}

main {
    margin: auto;
}
```
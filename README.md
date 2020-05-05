# SimpleMath
SimpleMath is a JavaScript display engine for mathematics that works in all browsers and that can be fully used offline. It used the syntax of LaTeX.

Check https://manfredschulenburg.github.io/simplemath/example.html to see what it looks like in action.


## Credits/Origin

The simplemath project has its origin in the extension of deck.js with the same name provided here: https://github.com/twitwi/deck.js/tree/master/extensions/simplemath. Get more information here: https://home.heeere.com/tech-deckjs-ext.html



## Usage example

SimpleMath can be included in any website with the following code:

<code>
  
  <script src="simplemath/extensions/includedeck/load.js"></script>
       <script>
            includedeck("profile-3", {
               PREFIX: "simplemath/" 
            })
        </script>
 </code>
 
## Criticism

*Advantages*
    
  * Works fully offline
  * Interprets LaTeX syntax
  * Generates MathML (web standard for maths)
  * Lets your browser render the MathML

*Disadvantages*
    
* Based on jquery. Therefore, it is for security reasons not supported by Android and iphone.
* It is not possible to join two characters: in e=mc^2 the "m" and the "c" are too much separated.
* Cannot be easily integrated in Markdown, i.e. with the LaTex-Syntax $ or $$ instead of the html code
* Does not support chemistry notation
		

*Conclusion*

In my view, in most cases the capabilities of SimpleMath are good enough for the use in websites. The fact that it is fully working offline is a real advantage.

Fuctionality-wise, SimpleMath could be a real alternative to MathJax. However, jquery would need to be replaced.
 

## Meta

Manfred Schulenburg

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/manfredschulenburg/simplemath/blob/master/LICENSE]

## Contributing

1. Fork it (<https://github.com/manfredschulenburg/simplemath/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

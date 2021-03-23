# lang-parser

ANTLR is a parser generator, in other words, a tool that helps you to create parser. A parser takes a piece of text and transform it in an organized structure. A parse tree or a Abstract Syntax Tree (AST) is a tree that describe the logical representation of a language. 

<p align="center">
  <img src="https://github.com/FelipeMolinari/lang-parser/blob/main/representation_ast_tree.png?raw=true" />
</p>


How it's works:

1. First of all, you need to define a lexer and a parser grammar.
2. Invoke ANTLR: It will generate a lexer and a parser in your target language. (In this project we are using Python, but could also be Java, C# and Javascript).
3. Use The Generated lexer and parser: You invoke them passing the code to recognize and they return to you a parse tree.


# Lexers and Parsers

Before looking into parsers, we need to first look into lexers. A lexer takes the individual characters and transform them in tokens.

```python
437 + 734
````

<p align="center">
  <img src="https://github.com/FelipeMolinari/lang-parser/blob/main/Tokenizacao.png?raw=true" />
</p>

The lexer scans the text and find '4', '3', '7' and then the space ' '. So it undestand that the first caracter is actually a number following by a '+' symbol and then finally it finds another number.

# Creating a Gammar 
   




# lang-parser

ANTLR is a parser generator, in other words, a tool that helps you to create parser. A parser takes a piece of text and transform it in an organized structure. A parse tree or a Abstract Syntax Tree (AST) is a tree that describe the logical representation of a language. 

<p align="center">
  <img src="https://github.com/FelipeMolinari/lang-parser/blob/main/representation_ast_tree.png?raw=true" />
</p>


How it's works:

1. First of all, you need to define a lexer and a parser grammar.
2. Invoke ANTLR: It will generate a lexer and a parser in your target language. (In this project we are using Python, but could also be Java, C# and Javascript).
3. Use The Generated lexer and parser: You invoke them passing the code to recognize and they return to you a parse tree.

## So let's start from the beginning:



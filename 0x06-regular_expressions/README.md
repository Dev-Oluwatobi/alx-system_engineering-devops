0x06. Regular expression
egular Expression
A regular expression, commonly called a “regexp”, is a sequence of characters that define a search pattern.  It is mainly for use in pattern matching with strings, or string matching (i.e. it operates like a “find and replace” command). While it is a very powerful tool, it is also very dangerous because of its complexity.



Some people, when confronted with a problem, think “I know, I’ll use regular expressions.”   Now they have two problems. (super classic joke in the industry)

One thing you have to be careful with is that different languages use different regexp engines. That means that a regexp in Python, for example, will be interpreted differently in Javascript:

Regular expressions are everywhere and software engineers, no matter their positions, will have to use them during their careers. System administrators and DevOps are the ones using them the most because they are very handy for log parsing.

Read about regexp:

http://www.regular-expressions.info/
http://www.w3schools.com/jsref/jsref_obj_regexp.asp Play with regexp (or compose them):

Ruby: http://rubular.com/

PHP/Javascript/Python: https://regex101.com/
Background Context
For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:
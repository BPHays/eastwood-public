# eastwood-public
Issue Tracker for CS240 eastwood linter

**Before posting:** make sure that your code compiles with the course C standard **c99**. If you have code that is not syntactially valid then you should be getting a syntax error from the linter. That said if the code compiles properly and you are getting a syntax error then it should be reported here. There are features of later standards, c11, and gnu extensions, gnu99, which are not supported. Also there are some [compiler extensions](https://gcc.gnu.org/onlinedocs/gcc/Warning-Options.html#index-Wpedantic), which are enabled even when using `-std=c99` that are not ISO. It would be nice to support these features, but that has not been our primary focus. If the code does not compile with the `-std=c99 -Werror -pedantic` flag that means it is using an extension which is not a part of the [ISO C standard](http://www.open-std.org/jtc1/sc22/wg14/www/standards).

This is a public issue tracker so **DO NOT** post chunks of your homework code here. Please just describe what you are seeing and if we are unable to replicate the bug then we may ask you to email us the code.

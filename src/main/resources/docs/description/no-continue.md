The continue statement terminates execution of the statements in the current iteration of the current or labeled loop, and continues execution of the loop with the next iteration. When used incorrectly it makes code less testable, less readable and less maintainable. Structured control flow statements such as if should be used instead.
This rule is aimed at preventing the use of continue statement. As such it warns whenever it sees continue statement.

```
//Bad:
var sum = 0, i;
for(i = 0;i < 10;i++) {
	if(i >= 5) {
		continue;
	}
a += i;
}

```

[Source](http://eslint.org/docs/rules/no-continue)

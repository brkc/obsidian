# bash
## History expansion
- [Event Designators](https://www.gnu.org/software/bash/manual/html_node/Event-Designators.html)
	- `!!`: last command
- [Word Designators](https://www.gnu.org/software/bash/manual/html_node/Word-Designators.html)
	- `!$`: last word
	- `!!:-`: everything except last word
- [Modifiers](https://www.gnu.org/software/bash/manual/html_node/Modifiers.html)
	- `!$:h`: remove trailing pathname
	- `!$:t`: remove leading pathname
	- `!$:r`: remove trailing _.suffix_
	- `!$:e`: remove all but trailing _.suffix_
	- `!!:gs/old/new`: substitute new for old

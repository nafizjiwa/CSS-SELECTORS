# CSS - ATTRIBUTE - SELECTORS

CSS Attribute Selectors<br>


| Selector | Example | Example description |
| --- | --------- | ---------- |
| [attribute] | [target] | Selects all elements with a target attribute |
| [attribute=value] | [target="_blank"] | Selects all elements with target="_blank" |	
| [attribute~=value] | [title~="flower"] | Selects all elements with a title attribute that contains a space-separated list of words, one of which is "flower" |
| [attribute\|=value] | [lang\|="en"]	|  Selects all elements with a lang attribute value starting with "en" |
| [attribute^=value] | a[href^="https"]	| Selects all <a> elements with a href attribute value starting with "https" |
| [attribute$=value] | a[href$=".pdf"]	| Selects all <a> elements with a href attribute value ending with ".pdf" |
| [attribute*=value] | a[href*="w3schools"]	| Selects all <a> elements with a href attribute value containing the substring "w3schools" |

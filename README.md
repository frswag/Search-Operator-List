# Search Operator List
Here is a list of all search operators I know about. The list will be updated if there are search operators that I missed. Feel free to make suggestions.

‎<br />

# Content
[Basic search operators](https://github.com/frswag/Search-Operator-List/edit/main/README.md#basic-search-operators)  
Number / time related search operators
URL / website search operators  
Data / datatype search operators
Money / crypto related search operators
Other search operators

<br />
<br />

# Basic search operators 
The most basic search operators that also gets used the most.

| Search Operator       | Explanation           | Example               | Reliable?             |
|-----------------------|-----------------------|-----------------------|-----------------------|
| " " | Searching for exact match | "Javascript" | Yes |
| OR | Searches for result that has either one of the words | Javascript OR python | Yes |
| ❘ | Same as OR | Javascript︳python | Yes |
| AND | Searching for results that include both words | Javascript AND python | Yes |
| - | Excludes results with the word | Javascript -python | Yes |
| * | Matching with similar results / acts as a wildcard | Java*script | Yes |
| ( ) | Group multiple searches | (Javascript OR python) calculator | Yes |
| _ | Acts as an autocomplete / acts as a wildcard | Newest _ commands | Depends |

# Number / time related search operators
Search operators that fall into the category of numbers typically deal with querying, filtering, or comparing numerical data.

| Search Operator       | Explanation           | Example               | Reliable?             |
|-----------------------|-----------------------|-----------------------|-----------------------|
| #..# | Searches for a value between two values | Javascript course $60..$80 | No |
| > | Greater than | Price>$50 | Yes |
| < | Less than | Price<$50 | Yes |
| >= | Greater than or equal to | Price>=$50 | Most of the time |
| <= | Less than or equal to | Price<=$50 | Most of the time |
| after: | Searching for results from after a particular date | Javascript versions after:2015 | Yes |
| before: | Searching for results from before a particular date | Javascript versions before:2015 | Yes |

# URL / website search operators
Search operators that are related to URL's / websites.

| Search Operator       | Explanation           | Example               | Reliable?             |
|-----------------------|-----------------------|-----------------------|-----------------------|
| site: | Searches for results from one specific site | site:javascript.com | Yes |
| inurl: | Searches for pages which have a particular word in the URL | inurl:javascript | Yes |
| allinurl: | Searches for pages which have multiple words in the URL | allinurl:javascript course | Yes |
| intext: | Searches for pages which includes a particular word | intext:programming | Yes |
| intitle: | Searches for pages with a specific word in the title | intitle:javascript | Yes |
| allintitle: | Searches for pages with multiple words in the title | intitle:javascript python | Yes |
| site: | Searches for results from only a particular website | site:javascript.com | Yes |
| related: | Searches for sites related to a specific domain | related:javascript.com | Yes |

# Data / datatype search operators
Search operators that are related to data / datatypes.

| define: | Searches for a definision of a word | define:javascript | Yes |
| filetype: | Searches for a specific type of file | filetype:pdf | Yes |
| ext: | Same as filetype: | filetype:pdf | Yes |
| source: | Search for results from a particular source in google news | source:javascript.com | Yes |

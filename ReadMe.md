# Postmortem
- [ ] select a better list
- [ ] automate the font collecting process with chrome extension for font detection + auto click (python, or frontend automation frameworks, selenium? )
- [ ] incorporate other metrics into algorithm (monthly visitors, company market cap)
- [ ] remove stupid font variables that are not actually fonts
- [ ] easier way to share the findings, in an interactive way (website, github pages?)

# dooblydoo
- `source .venv/bin/activate`
- not all html is loaded upon first request
- different sections can have different fonts

- A ranking algorithm is a procedure used to rank items in a dataset according to some criterion. 
    - two categories: deterministic and probabilistic
    - deterministic: order of the items in the ranked list is fixed, and does not change regardless of the input data
        - grocery item ordering (category, alphabet)
    - probabilistic: order of the item is determined by the input data
        - search ranking
- binary ranking algo
    - rank by feature - more accurate and computation
    - rank by frequency - less accurate and computation
    - in regards to a reference, using their relative importance

- my assumptions
    - first font is the most significant
    - use a exponential fall off for ranking, because the others are fall back fonts
- algo: 
    - rank            0,    1,     2
    - company1:      [a,    b,     c]
    - company2:      [a,    b,     d]
    - A = 2 * 0,5 ^ 0 = 2
    - B = 2 * 0.5 ^ 1 = 1
    - C = 1 * 0.5 ^ 2 = .25
    - D = 1 * 0.5 ^ 2 = .25



# timesheet
49:23
1:00:00
20:00
52:00
30:00
20:00
1:00:00
1:30:00
30:00
30:00
1:13:00

30:00
30:00
30:00
10:00
1:00:00

# algo links
https://vitalflux.com/ranking-algorithms-types-concepts-examples/#:~:text=Conclusion-,What%20is%20a%20Ranking%20Algorithm%3F,recommender%20systems%2C%20and%20machine%20learning
https://stackoverflow.com/questions/6996632/multiple-fonts-in-font-family-property


# software links
https://regexr.com/ 
https://regex101.com/ 
https://stackoverflow.com/questions/1274057/how-do-i-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitignore 
- python
https://stackoverflow.com/questions/41972261/what-is-a-virtualenv-and-why-should-i-use-one 
https://docs.python.org/3/library/venv.html 
https://code.visualstudio.com/docs/python/environments 
https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/
https://stackoverflow.com/questions/50821312/meaning-of-python-m-flag
https://stackoverflow.com/questions/58119823/jupyter-notebooks-in-visual-studio-code-does-not-use-the-active-virtual-environm 
https://stackoverflow.com/questions/13694034/is-a-python-list-guaranteed-to-have-its-elements-stay-in-the-order-they-are-inse 
https://stackoverflow.com/questions/4527942/comparing-two-dictionaries-and-checking-how-many-key-value-pairs-are-equal
https://realpython.com/python-assert-statement/
https://www.w3schools.com/python/python_try_except.asp 
https://docs.python.org/3/tutorial/errors.html 
https://www.geeksforgeeks.org/ternary-operator-in-python/
https://www.programiz.com/python-programming/methods/string/lower
https://realpython.com/python-string-contains-substring/ 
https://www.geeksforgeeks.org/python-remove-empty-strings-from-list-of-strings/
https://www.geeksforgeeks.org/python-string-find/ 
https://www.w3schools.com/python/python_regex.asp 
https://www.w3schools.com/python/python_regex.asp#matchobject 
https://stackoverflow.com/questions/5327206/regex-match-digits-comma-and-semicolon 
https://stackoverflow.com/questions/18024298/regular-expression-starting-and-ending-with-a-character-string 
https://stackoverflow.com/questions/9589074/regex-should-hyphens-be-escaped 
https://stackoverflow.com/questions/6109882/regex-match-all-characters-between-two-strings 
https://stackoverflow.com/questions/28265313/how-to-check-if-a-string-starts-with-double-quotes 
https://stackoverflow.com/questions/30221835/python-regex-pattern-max-length-in-re-compile 
https://stackoverflow.com/questions/28539253/python-regex-bad-character-range 
https://www.programiz.com/python-programming/methods/built-in/sorted
https://stackoverflow.com/questions/613183/how-do-i-sort-a-dictionary-by-value
https://realpython.com/iterate-through-dictionary-python/#iterating-through-items
https://realpython.com/beautiful-soup-web-scraper-python/ 
https://www.crummy.com/software/BeautifulSoup/bs4/doc/ 
https://www.geeksforgeeks.org/get-post-requests-using-python/ 
- pandas
https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf 
https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html
https://www.geeksforgeeks.org/how-to-create-an-empty-dataframe-and-append-rows-columns-to-it-in-pandas/ 
https://www.geeksforgeeks.org/how-to-create-dataframe-from-dictionary-in-python-pandas/
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sort_values.html?highlight=sort_values#pandas.DataFrame.sort_values
https://stackoverflow.com/questions/16476924/how-to-iterate-over-rows-in-a-dataframe-in-pandas 
https://stackoverflow.com/questions/17071871/how-do-i-select-rows-from-a-dataframe-based-on-column-values 
https://stackoverflow.com/questions/58305156/match-values-from-dictionary-to-dataframe-row-values-and-add-data-to-that-row
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.apply.html?highlight=apply#pandas.DataFrame.apply
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.concat.html?highlight=concat#pandas.concat
- visualization
https://stackoverflow.com/questions/66557543/valueerror-mime-type-rendering-requires-nbformat-4-2-0-but-it-is-not-installed
https://www.geeksforgeeks.org/data-visualization-with-python/
https://www.geeksforgeeks.org/pie-plot-using-plotly-in-python/?ref=lbp
https://www.geeksforgeeks.org/bar-chart-using-plotly-in-python/?ref=lbp
https://www.geeksforgeeks.org/histogram-using-plotly-in-python/

# Other links
https://www.elegantthemes.com/blog/wordpress/how-to-see-what-font-a-website-is-using

# sheet music
keeping some sheet music under version control

# how does this work?

i added a textconv rule for zip files to this project's .gitconfig

```
[diff "zip"]
	textconv = unzip -c -a
```

and i specified that .mscz files should use the zip rule in .gitattributes




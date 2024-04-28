# XRB VSCode

This extension provides support for the XRB language in Visual Studio Code.

## Support

### File Extensions

- `.xrb` is the canonical file extension.
- `.xnode` is a legacy file extension from `utopia`.
- `.trenni` is a legacy file extension from `trenni`.

### `XRB` Heredocs

``` ruby
source = <<~'XRB'
	<p>hello</p>
	#{"foo" + "bar"}
	<?r hello # bar ?>
XRB
```

### `XRB` Markdown

~~~ markdown
``` xrb
<p>hello</p>
#{"foo" + 10}
<?r hello # bar ?>
```
~~~
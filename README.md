# Varnam Webpage Embed Plugin

Embed Varnam input tool in any webpage input fields, contenteditable.

```html
<textarea id="input"></textarea>

<link href="https://api.varnamproject.com/embed.css" rel="stylesheet" />
<script src="https://api.varnamproject.com/embed.js"></script>
<script type="text/javascript">
  const input = document.getElementById("input");
  plugVarnam(input, {
    schemeID: "ml",
  });
</script>
```

## Demo

[**See this codepen**](https://codepen.io/subins2000/pen/bGxxBeX)

## Schemes
1. `as` - Assamese
2. `bn` - Bengali
3. `en` - English
4. `gu` - Gujarati
5. `hi` - Hindi
6. `kn` - Kannada
7. `ml-inscript` - Malayalam with incript layout 
8. `ml` -  Malayalam
9. `mr` - Marati
10. `ne` - Nepalise
11. `or` - Odia
12. `pa` - Punjabi
13. `sa` - Sanskrit
14. `ta` - Tamil
15. `te` - Telugu

## Other

Thanks to [this vite template](https://github.com/AndrewBastin/vue3-embedded-library-template) for making things easier.

Release posts:

- https://twitter.com/SubinSiby/status/1637470104626814978?s=19
- https://aana.site/@subins2000/110050565970026218

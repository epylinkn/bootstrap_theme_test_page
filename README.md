Bootstrap Theme Test Page
=========================

A quick one pager that puts all of twitter bootstrap's styling into one long and condensed page for quick overview.

Basically, ran this jQuery function on each bootstrap page that has style examples:

```javascript
$('.bs-docs-example').each(function() { console.log($('<div>').append($(this)).html()) });
```

## Make it go

```bash
cd bootstrap_theme_test_page
python -m SimpleHTTPServer
open "http://localhost:8000"
```

The page uses CDNs. If testing your own custom themes, you'll probably want to change those.

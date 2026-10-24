# things-link

A one-page redirect that makes Things 3 links tappable in apps that only open `https://` links.

Put a Things URL after the `#`:

```
https://<user>.github.io/things-link/#things:///add?title=Buy%20milk
```

The page opens Things with that link and shows a preview of what will be added. Everything after the `#` stays in the browser and is never sent to GitHub.

Only commands that create new items (`add`, `add-project`, `json`) are allowed. Links that edit existing data or contain an auth token are refused.

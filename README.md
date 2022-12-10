# Example for issue 1458

https://github.com/tailwindlabs/tailwindcss.com/issues/1458

In this project, if you run `npm run lint` - it all passes.

If you remove `lang="postcss"` from the `style` tag in `routes/+page.svelte` then the linter fails with the following message:

```
5:29  error  Semicolon or block is expected ParseError

✖ 1 problem (1 error, 0 warnings)
```
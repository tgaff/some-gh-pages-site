This page should be at `[ROOT]/bad-links/nested/page.md`

- [bad link 1 - relative same directory](relative-bad-page.md)
- [good link - ../ up to parent and down again](../nested/page.md)
- [bad link 2 - ../ up to parent and down again](../nested/nope.md)
- [good link - slash](/bad-links/nested/page.md)
- [bad link 3 - slash](/bad-links/nested/no-existe.md)

You should see a total of 3 errors for this page in the checks.

This page should be at `[ROOT]/bad-links/nested/page.md`

- [bad link 1 - relative same directory](bad-link-1.md)
- [good link - ../ up to parent and down again](../nested/page.md)
- [bad link 2 - ../ up to parent and down again](../nested/bad-link-2.md)
- [good link - slash](/bad-links/nested/page.md)
- [bad link 3 - slash](/bad-links/nested/bad-link-3.md)

You should see a total of 3 errors for this page in the checks.
And 1 error in the "unreferenced page".

**total broken links 4**

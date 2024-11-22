A guide to implementing Previous and Next navigation links in Markdown README files.

# Adding Navigation between README files
We can add Next and Previous buttons in our README files. We can use Markdown links to navigate between the files. These buttons won't look exactly like buttons but can resemble navigation links.

---

## Why Use Navigation Links?

Adding **Previous** and **Next** buttons makes it easier for readers to navigate between sections or related README files, especially in multi-file documentation projects.

---

## Example with Next and Previous Links
Lets consdier you have a starting file dummyStart.md. We can add only next button to it as it is the beginnin page.
### Example Code
```markdown
# Dummy Starting page
Please click on next for next page

---

[Next: DUMMY NEXT](./dummyNext.md)
```

### Output
# Dummy Starting page
Please click on next for next page

---

[Next: DUMMY NEXT](./dummyNext.md)


Lets consider you have navigated to dummy next page and it looks like below with previous and next buttons.
### Example Code
```markdown
# This is Next placeholder
- Click on Prev button and you will land on dummy Prev page
- Click on Next button and you will land on dummy Next Next page

---

[Previous: DUMMY PREV](./dummyPrev.md) | [Next: DUMMY NEXT NEXT](./dummyNextNext.md)
```

### Output
# This is Next placeholder
- Click on Prev button and you will land on dummy Prev page
- Click on Next button and you will land on dummy Next Next page


---

[Previous: DUMMY PREV](./dummyPrev.md) | [Next: DUMMY NEXT NEXT](./dummyNextNext.md)


Next Next page looks like below
### Example Code
```markdown
# This is dummy Next Next page
Please go to main page [Navigation Page](./navigations.md)

Click on Prev button and you will land on dummy Next page

---
[Next: DUMMY PREV](./dummyNext.md)

```

### Output
# This is dummy Next Next page
Please go to main page [Navigation Page](./navigations.md)

Click on Prev button and you will land on dummy Next page

---
[Next: DUMMY PREV](./dummyNext.md)


## Enhanced Navigation (Optional)
If you want the links to stand out more:
- Use emojis for arrows
  ```markdown
  [⬅️ Previous: DUMMY PREV](./dummyPrev.md) | [➡️ Next: DUMMY PREV](./dummyNext.md)
  ```
  Output

  [⬅️ Previous: DUMMY PREV](./dummyPrev.md) | [➡️ Next: DUMMY PREV](./dummyNext.md)
- Use horizontal rules to separate navigation links from content
  ```markdown
  ---
  [⬅️ Previous: DUMMY PREV](./dummyPrev.md) | [➡️ Next: DUMMY PREV](./dummyNext.md)
  ---
  ```
  Output
  
  ---
  [⬅️ Previous: DUMMY PREV](./dummyPrev.md) | [➡️ Next: DUMMY PREV](./dummyNext.md)
  ---

## More Examples
- Align Prev and Next buttons to beginning and end of the page: [Custom HTML for Alignment](./navigation-html.md)


## Practical Tips
- Consistency: Use the same style across all README files in the project.
- Cross-Check Links: Ensure all links point to the correct files and sections.
- Fallback Plan: Use simple Markdown links for maximum compatibility.


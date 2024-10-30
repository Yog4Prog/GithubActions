# Example with <p> Tags

This text is outside any `<p>` tag, so it’s just regular Markdown text.

<p>This text is wrapped in a paragraph tag, so it will be separated with a bit of space before and after. You can also use this to enforce line breaks and make sure the text behaves as a paragraph.</p>

## Another Example Inside a Table

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td><p>This is a paragraph inside a table cell. Using `<p>` here helps control spacing and allows for text wrapping within the table cell.</p></td>
        <td><p>Another paragraph, which should also wrap properly if the Markdown renderer supports it.</p></td>
    </tr>
</table>

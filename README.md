# Nested Table Example

This is an example of a nested table using HTML syntax within a Markdown file.

<table>
    <tr>
        <th>Main Header 1</th>
        <th>Main Header 2</th>
    </tr>
    <tr>
        <td>
            Sub-table 1
            <table>
                <tr>
                    <th>Sub-header 1</th>
                    <th>Sub-header 2</th>
                </tr>
                <tr>
                    <td>Row 1, Cell 1</td>
                    <td style="word-wrap: break-word; width: 200px;">
                        This is an example text that consists of exactly fifty words. <br/>It serves as a placeholder for content, demonstrating how text can fill up a cell in a table.<br/> You can replace this with any relevant information as needed in your Markdown documentation.
                    </td>
                </tr>
                <tr>
                    <td>Row 2, Cell 1</td>
                    <td>Row 2, Cell 2</td>
                </tr>
            </table>
        </td>
        <td>
            Sub-table 2
            <table>
                <tr>
                    <th>Sub-header A</th>
                    <th>Sub-header B</th>
                </tr>
                <tr>
                    <td>Row 1, Cell A</td>
                    <td>Row 1, Cell B</td>
                </tr>
                <tr>
                    <td>Row 2, Cell A</td>
                    <td>Row 2, Cell B</td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td>Main Data 1</td>
        <td>Main Data 2</td>
    </tr>
</table>

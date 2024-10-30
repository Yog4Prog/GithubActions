# Nested Table Example

This is an example of a nested table using HTML syntax within a Markdown file.

<table border="1" style="border-collapse: collapse;">
    <tr>
        <th>Main Header 1</th>
        <th>Main Header 2</th>
    </tr>
    <tr>
        <td style="width: 75px;">
            Sub-table 1
            <table border="1" style="border-collapse: collapse;">
                <tr>
                    <th style="width: 75px;">Sub-header 1</th>
                    <th style="width: 75px;">Sub-header 2</th>
                </tr>
                <tr>
                    <td style="width: 75px;">Row 1, Cell 1</td>
                    <td style="width: 75px; word-wrap: break-word;">
                        This is an example text that consists of exactly fifty words. It serves as a placeholder for content, demonstrating how text can fill up a cell in a table. You can replace this with any relevant information as needed in your Markdown documentation.
                    </td>
                </tr>
                <tr>
                    <td style="width: 75px;">Row 2, Cell 1</td>
                    <td style="width: 75px;">Row 2, Cell 2</td>
                </tr>
            </table>
        </td>
        <td style="width: 75px;">
            Sub-table 2
            <table border="1" style="border-collapse: collapse;">
                <tr>
                    <th style="width: 75px;">Sub-header A</th>
                    <th style="width: 75px;">Sub-header B</th>
                </tr>
                <tr>
                    <td style="width: 75px;">Row 1, Cell A</td>
                    <td style="width: 75px;">Row 1, Cell B</td>
                </tr>
                <tr>
                    <td style="width: 75px;">Row 2, Cell A</td>
                    <td style="width: 75px;">Row 2, Cell B</td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td>Main Data 1</td>
        <td>Main Data 2</td>
    </tr>
</table>

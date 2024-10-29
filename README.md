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
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 1, Cell 1</div>
                    </td>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">
                            This is an example text that consists of exactly fifty words. It serves as a placeholder for content, demonstrating how text can fill up a cell in a table. You can replace this with any relevant information as needed in your Markdown documentation.
                        </div>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 2, Cell 1</div>
                    </td>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 2, Cell 2</div>
                    </td>
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
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 1, Cell A</div>
                    </td>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 1, Cell B</div>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 2, Cell A</div>
                    </td>
                    <td>
                        <div style="width: 75px; overflow-wrap: break-word;">Row 2, Cell B</div>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td>Main Data 1</td>
        <td>Main Data 2</td>
    </tr>
</table>

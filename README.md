# Nested Table with Wrapped Text

| Column 1               | Column 2             | Column 3    |
|------------------------|----------------------|-------------|
| <table>                | More Content in Column 2 | Simple Text |
| <tr>                   |                      |             |
| <td>                   |                      |             |
| <table>                |                      |             |
| <tr>                   | <th>Nested Column 1</th> | <th>Nested Column 2</th> |
| <tr>                   |                      |             |
| <td>                   | <p>**Short text (around 50 words):** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p> | Additional Data |
| <tr>                   | <td>Nested Data 1</td> | <td>Nested Data 2</td> |
| </tr>                  | </tr>                | </tr>       |
| </table>              |                      |             |

# Nested Table with Wrapped Text

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  table, th, td {
    border: 1px solid black;
    padding: 8px;
    word-wrap: break-word;
    white-space: normal;
  }
</style>

<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
    <th>Column 3</th>
  </tr>
  <tr>
    <td>
      <!-- Nested Table with Wrapped Text -->
      <table>
        <tr>
          <th>Nested Column 1</th>
          <th>Nested Column 2</th>
        </tr>
        <tr>
          <td>
            <p>
              **Short text (around 50 words)**: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
          </td>
          <td>Additional Data</td>
        </tr>
        <tr>
          <td>Nested Data 1</td>
          <td>Nested Data 2</td>
        </tr>
      </table>
    </td>
    <td>
      More Content in Column 2
    </td>
    <td>Simple Text</td>
  </tr>
</table>

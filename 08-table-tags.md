# Working with tabular data

The `<table> ... </table>` tag is used to make the specific contents of the web page in a a more systematic & organised manner making it easier to read & understand. This tag makes a table & arranges the wrapped data in a tabular form consisting of many rows, with each row containing a respective relative heading or a title.

Some cumpolsary tags are used inside the `<table> ... </table>` tag so that the browser can differentiate between contents & display the contents accordingly. The tags are displayed below along with their description & their function in the webpage.

- `<thead> ... </thead>` tag is used to instruct the browser that anything wrapped inside these tags is the heading of the current table. It has no visual representation in the webpage

- `<tbody> ... </tbody>` tag is same as the previous THEAD tag but the only difference is that it instructs the browser that anything wrapped inside these tags is the body of the current active table.

- `<tr> ... </tr>` tag is used to declare & make a row in the current active table.

- `<th> ... </th>` tag is used to declare a heading to the newly created row. IT IS VERY DIFFERENT FROM THE THEAD TAG & HAS A PROPER VISUAL REPRESENTATION IN THE WEBPAGE. PLEASE DO NOT GET CONFUSED.

- `<td> ... </td>` tag is used to define the table data in the previously created rows. This can also be called the main content inside the table that would be read more often by the user visiting the webpage.

An example of the table tag with all the above tags is as follows,

```
<body>
  <table>
    <thead>
      <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Counrty Of Residence</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Mickey</td>
        <td>Mouse</td>
        <td>Disneyland</td>
      </tr>
    </tbody>
  </table>
</body>
```

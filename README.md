Active learning: Adding table structure

1. First of all, make a local copy of spending-record.html and minimal-table.css in a new folder.

2. Try opening it in a browser — You'll see that it looks OK, but it could stand to be improved. The "SUM" row that contains a summation of the spent amounts seems to be in the wrong place, and there are some details missing from the code.

3. Put the obvious headers row inside a &lt;thead&gt; element, the "SUM" row inside a &lt;tfoot&gt; element, and the rest of the content inside a &lt;tbody&gt; element.

4. Save and refresh, and you'll see that adding the &lt;tfoot&gt; element has caused the "SUM" row to go down to the bottom of the table.

5. Next, add a colspan attribute to make the "SUM" cell span across the first four columns, so the actual number appears at the bottom of the "Cost" column.

6. Let's add some simple extra styling to the table, to give you an idea of how useful these elements are for applying CSS. Inside the head of your HTML document, you'll see an empty &lt;style&gt; element.

Live web: https://gitthuma.github.io/adding_table_structure/

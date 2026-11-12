Replace the "No expenses yet" placeholder text inside your expenses section with a properly structured HTML table.

Use <thead> for the header row and <tbody> for the data rows.

Include column headers for Name, Amount, Category, and Date using <th>.

Add at least 5 rows of sample hardcoded expense data using <td>.

Style the table in your style.css file - add borders using border-collapse: collapse, padding inside cells, a colored header row, and alternating row background colors using tr:nth-child(even).


2. Upgrade the Add Expense Form

Improve the form section you built last week:

Replace the plain text category input with a <select> dropdown containing at least 5 options: Food, Transport, Rent, Entertainment, and Other.

Wrap all your form inputs inside a proper <form> element.

Add a <button type="button"> labeled "Add Expense" - it won't do anything yet, that comes in Week 7.

Make sure every input has a clear, matching id attribute (e.g., id="expense-name", id="expense-amount", id="expense-category"). These IDs will be used heavily when JavaScript arrives in Week 6.


3. Add Multimedia Content

Add a small logo or icon image near your main heading using the <img> tag with proper src, alt, and width attributes.

Embed a relevant YouTube video (a budgeting tip video, or any video of your choice) somewhere on the page using an <iframe>. Set the width, height, title, and frameborder attributes correctly.


4. Add an Interactive Element

Add a <details> and <summary> element to your page - for example, a collapsible "How to use this tracker" section that explains what the form does.

Apply a :hover style to your table rows in CSS so they subtly change background color when the user moves their mouse over them.

Apply cursor: pointer to your button so it shows the hand cursor on hover.


5. Apply Advanced CSS Selectors

Using what you learned in the More CSS Selectors lesson, apply at least three of the following in your stylesheet:

A descendant selector (e.g., .expenses-section td)

A direct child selector (e.g., .add-expense-section > input)

A pseudo-class based on position (e.g., tr:first-child, tr:nth-child(even))

A negation pseudo-class (e.g., input:not([type="submit"]))

A focus state for your inputs (e.g., input:focus)

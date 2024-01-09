# Product-Registration-
The provided code appears to be an HTML document that includes some JavaScript for handling product registration and details display. 


HTML Structure:
The document starts with the usual HTML5 doctype declaration and sets the language to English.
The <head> section includes metadata, the title of the page, links to Bootstrap CSS and Bootstrap Icons, and a <script> tag containing JavaScript functions.
The <style> section includes some custom styling for definition list elements (<dd> and <dt>).
JavaScript Functions:
RegisterClick(): This function is triggered when the "Register" button is clicked. It sets the display of the detailsContainer to block and updates various elements with values from the input fields. It also checks the status of a checkbox and updates the stock status accordingly.

EditClick(): This function is triggered when the "Edit Details" button is clicked. It currently changes the text of the "Register" button to "Update."

HTML Body:
The <body> tag has the class "container-fluid" for Bootstrap styling.
A button with the label "Register Product" is present, and it triggers a modal with a form for registering a new product.
The modal includes form elements such as input fields for product name and price, a select dropdown for the city, and a checkbox for stock availability.
There are two buttons in the modal: "Register" and "Cancel."
Below the modal, there is a hidden container (detailsContainer) that displays product details when the product is registered. It includes a button to edit the details.
Finally, there are script tags at the end, importing jQuery and Bootstrap JS files.

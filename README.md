# The Bookclub

## List of books avalible

Due Date: **15th December 2020**
Classwork: **Component and Dynamic Data**
Teacher: **James Heggs**
Team: **Readers (Samantha Burke, Winndie Fan, Rebeca Sciamanna, Anita Caron)**

### Book container
The book container comprises three components: book, stock and request. 

All three components contains a dynamic datasource from JSON files on Github repo https://github.com/yrtt-readers/the-bookclub.git, or Open library API https://openlibrary.org/dev/docs/api/books.

### Book component
Book summary is a flexible textbox, if the user clicks [More] a full description gets displayed (max words), if the user clicks [Less] then a short description gets displayed (x number of words).
Thumbnail is an image tag, displaying pre pre-rendered images when the thumbnail is not available.

### Stock component
Number of copies in stock (books availible) are be grouped by postcode and quantity.
If the book is not in stock N/A will be displayed.


### Request component
If the user clicks on the [Request] button to open the request component, he/she can enter the number of copies to request, postcode will be filled from the user's information in the database.
[Request] component will also display awaiting requests with postcode and quantity.

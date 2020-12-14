# The Bookclub

## List of books avalible

Due Date: 15 Dec, 2020
Classwork: Component and Dynamic Data
Teacher: James Heggs
Team: Readers (Samantha Burke, Winndie Fan, Rebeca Sciamanna, Anita Caron)

### Book container
The book container comprises three components: book, stock and request. All three components contain dynamic datasource from JSON files on github repo https://github.com/yrtt-readers/the-bookclub.git, or 
Open library API https://openlibrary.org/dev/docs/api/books.

### Book component
Book summary is a flexible textbox, user click [More] full description (max words), click [Less] short description (x number of words).

Thumbnail is an image tag, displaying pre pre-rendered images when the thumbnail is not available.

### Stock component
Number of copies in stock will be group by postcode + sum(qty)
books out of stock will display N/A


### Request component
User click on [Request] button to open request component, h/she can enter number of copies request, postcode will be filled from user's information in database.

[Request] component will also display awaiting requests with postcode+qty.

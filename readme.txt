WAREHOUSE ORGANIZER

1 - Purpose
2 - Technologies
3 - Functionality
4 - Styling
5 - Contributors


1 PURPOSE

· Get the location of the "drugs" up to date.
· Relocate matching "batches" to find them in only one position while keeping track of the real quantity.
· Locate received "batches" with already existing ones.
· Create a digital back up for the stock cards.


2 TECHNOLOGIES

· HTML5
· CSS
· JavaScript
	· Nodejs: //Dependencies in alphabetical order//
		· body-parser
		· connect-flash
		· express
		· express-session
		. ejs
		· method-override
		· mongoose
		· passport + passport local + passport-local-mongoose


3 FUNCTIONALITY

· The main objective is to keep it as simple and intuitive as possible to make it friendly to unexperienced users.
	· The landing page will be a login page.
	· The main page will display a list of the "drugs" with a picture of each one in a square. By clicking on it a list of all the batches will be displayed or it will redirect the user to a page with the list. Displaying its details may be an option and by clicking on it, it will send us to a "batch" page where all the details as well as the comments will be shown from the newest to the oldest.
		· While interacting with the batch:
			· Two options will be given: ADD and PICK (the second one selected by default) (Also a log out button).
				If PICK is selected:
					1· The picking list number and the customers details will be provided.
					2· The quantity issued will be provided.
					3· After accepting the inputed quantity, a line will display in the comments section showing the customer's details, the picking list number, the quantity issued, the remaining quantity and the employee's name. A comment will be optional and used only in exceptional cases (i.e. damaged stock found).
					4· There will be the possibility to edit every entry but only by it's creator or a super user and it MUST be accompanied of a comment and the amended line will be kept in record for future inquiries.

												OR

					5· The picking list number and the costumer details will be asked at the beginning of the picking in order to keep a clearer record of the picking minimizing the risk of mistakes.
						· Follow from 2.

				If ADD is selected:
					1· The supplier, the GRN number and the quantity to be added will be provided.
					2· A new line will be displayed with the supplier's name, the GRN number, the quantity added and the employee's name.
					3. Comments will be optional and editable. A record of edited lines will be saved.

												OR

					4. Supplier's name and the GRN number will be provided at the beginning of the work assuming that more than 1 product is going to be located / relocated in the same session.

			· While picking is finished, ask for the number of boxes or pallets needed and create as many sticking labels as needed

			(Add a search engine)


4 STYILING

· It's very important to keep things in a proper size in order to be friendly with people with sight problems. Different colors well contrasted will be capital (i.e. avoid using different shades of the same color) and a readable font size that could be customizable in at least 3 sizes: Normal, Big, Extra Big. High contrast won't be necessary. The using of frameworks as bootstrap would be acceptable.


5 CONTRIBUTORS

· Feel free to fork the code, improve it, change it, style it. A mention will be appreciated and it won't hurt you :)
· Contributing to this branch will be accepted in later phases of the development. I would like to thank in advance to everyone willing to contribute to this project.
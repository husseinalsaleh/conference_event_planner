# Conference Expense Planner app

The **Conference Expense Planner** app project, represents the front end of an application that allows the user to price out the expenses related to hosting a conference at a convention center.

The **Conference Expense Planner** has a landing page, a product selection page, and a pop-up summary window. The product selection page allows users to select their rooms, their add-ons, and meals. Based on those selections, it provides pricing. The pop-up window summarizes the expenses in a table based on the user's selections from the product selection page.

### Landing page

Features on this page include:

- A paragraph about the company
- A background image
- A **Get Started** button linking to the product selection page

You landing page will look something like this:  

![image](https://github.com/user-attachments/assets/5f264d3d-8ee0-4abf-9274-35deedb0e8ce)

### Product selection page

After selecting **Get Started**, the application direct the user to the product selection page. This page allows users to select rooms in the venue, add-ons needed for presentations such as microphones and speakers, and meals they would like catered for the participants. This page have three sections: room selection, add-ons, and meals. Each section should have its own header and also a page header with navigation to each section.


##### Room selection and navigation bar

Users select from 5 room types:

- Auditorium hall – capacity 200, $5500 ea
- Conference room – capacity 15, $3500 ea
- Presentation room – capacity 50, presentation room, $700 ea
- Large meeting room – capacity 10, $900 ea
- Small meeting room – small meeting room, capacity 5, $1100 ea


The product selection page also have a header with a navigation bar. The navigation bar display a **Show Details** button, which opens a pop-up window displaying data related to the user's selections.

![{0733C1CF-F720-4FBC-8E3A-622706A7D3E0}](https://github.com/user-attachments/assets/0ed42733-333a-4448-b567-5e60c9246e59)

##### Add-ons selection

Users can select their audio/visual equipment in the add-ons section:

- Speakers – $35 ea
- Microphones – $45 ea
- Whiteboards – $80 ea
- Projectors – $200 ea
- Signage – $80 ea

![{35FA251F-5F3C-4D7B-9F1A-47B6DFA536CD}](https://github.com/user-attachments/assets/8c7eace2-88e5-4e1e-99b7-b478c3888a0e)


##### Meals selection

Users can select the following options for meals in the meals section:

- Breakfast – $50 per person
- Lunch – $60 per person
- High tea – $25 per person
- Dinner – $70 per person

![{553941AA-FD77-46B3-B79C-CB3C788E7C59}](https://github.com/user-attachments/assets/ba82712b-9d65-47aa-82a7-d114ea6d6ae7)


##### Sample product selection page (all sections):

![image](https://github.com/user-attachments/assets/31d92bc7-7e37-4008-9d8c-bd3f0958e81d)


### Show details pop-up

The users can see the details of their selections. For this element, they can access this information through a **Show Details** button in the header. When the user selects the button, a window pops up displaying a four-column table. Each row of the table contains the selection type, its unit cost, the quantity indicated, and the subtotal for the quantity of that item type. It will also display the total cost for all items.

![{6FFCD291-83A9-46DD-BB92-297318CA5CAA}](https://github.com/user-attachments/assets/bbc64d26-6f53-4545-8a41-acfed89f7a5b)


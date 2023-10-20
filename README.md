Currently, the app renders a HomePage component that fetches and displays all adoptable pets (you can view the code for this page in src/pages/home/index.js). We have also built a PetDetailsPage to display the details for a particular pet (src/pages/detail/index.js), but this component will not render until you create a route to display it.

Your objective will be to add client-side routing to the application using React Router so that:

The HomePage component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.
The PetDetailsPage page displays when the browser’s current URL includes a specific pet’s id.
The PetDetailsPage displays data for the correct pet based on the id in the URL parameters’ values.
When the user searches for a pet in the search bar, they are redirected to the SearchPage, which uses the query parameter called name to filter pets by name.
When a user clicks a pet whose details are not available, they are redirected to a PetNotFoundPage.
From the PetNotFound page, users can click “Go Home” button that will take them to the root path page.
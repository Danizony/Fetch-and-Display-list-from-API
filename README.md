                             --Fetch and Display List from an API--
Objective: The goal of this project is to build a functional React component thafetches data from an API and displays a list of items. You will also create a reusable list component to follow best practices in component reusability and separation of concerns.

				--Task Breakdown--
1. Fetching Data from an API: Use the fetch API or Axios to retrieve data from a   public API(e.g, JSONPlaceholder, Rick and Morty API, or any other freeAPI). S   tore the fetched data in React State using the useState hook. Use the useEffe   ct hook to fetch data when the component mounts. Handle loading states and er   ror handling gracefully.
2. Creating a Reusable List Component: Develop a reusable ListComponent that tak   es in an array of items as props. Render each item dynamically inside the lis   t. Ensure flexibility by allowing customization through props(e.g., passing a   custom render function for list items).
3. Rendering the List in a Parent Component: Use the `ListComponent` inside a pa   rent component and pass the fetched data as props. Display a loading indicato   r while data is being fetched. Show an error message if the API request fails

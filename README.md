# Chef's Menu Manager — MAST5112 Part 3

## Project
This React Native application helps the chef at Christoffel's Restaurant manage the restaurant menu.

## Features completed
- Add a menu item with a dish name, description, course and price.
- View menu items in a scrolling list.
- Edit and update an existing menu item.
- Delete a menu item after confirmation.
- Search for a dish by its name.
- Filter dishes by Starter, Main Course or Dessert.
- Clear the search and filter to display the full menu again.
- Display the total number of menu items.
- Calculate the average price of all menu items.
- Count the number of items in each course.
- Validate required fields and price values.
- Show success, error and confirmation messages.
- Use consistent styling, reusable helper functions and meaningful variable names.

## Changes made since Part 2
1. Added an edit function that loads an existing dish into the form.
2. Added an update function that immediately changes the selected dish.
3. Added a delete function with a confirmation message.
4. Added search by dish name.
5. Added course filters for All, Starter, Main Course and Dessert.
6. Added a clear search/filter function.
7. Added menu statistics: total items, average price and item counts by course.
8. Improved validation and user feedback.
9. Improved the layout, spacing, labels and empty-state messages.
10. Organised the code using clear names and reusable functions.

## How to run
1. Open the React Native project used for Part 2.
2. Replace the contents of `App.tsx` with the supplied `App.tsx` file.
3. Keep the existing project configuration and dependencies.
4. Ensure `react-native-safe-area-context` is installed because the app imports `SafeAreaView` from it.
5. Start the project using the command appropriate for the existing project, for example `npx expo start` for an Expo project.
6. Test all the features listed above.

## Important note about data
This version stores menu items in React state while the app is running. It does not yet save items permanently to a database or device storage. Added items may disappear after the app is closed or reloaded. Do not describe the application as having permanent storage unless that feature is added and tested.

## Testing checklist
- [ ] Add a valid dish and confirm that it appears.
- [ ] Try saving an empty form and check the validation messages.
- [ ] Try entering zero, a negative value or non-numeric price.
- [ ] Edit a dish and confirm that the changes appear.
- [ ] Delete a dish and confirm the deletion prompt appears.
- [ ] Search for a dish by name.
- [ ] Filter by Starter, Main Course and Dessert.
- [ ] Clear search/filter and confirm all items return.
- [ ] Check total items, average price and course counts.
- [ ] Restart the app and note that state-only data is not permanent.

## Submission items from the brief
- This README file with a change log.
- Latest project code uploaded to GitHub.
- A 5–8 minute screen-recording demonstration uploaded to YouTube as Unlisted.
- The GitHub repository link and accessible YouTube video link included in the submission.

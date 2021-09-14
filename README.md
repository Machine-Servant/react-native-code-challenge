# react-native-code-challenge
You have been challenged.

## What to build

Build a React Native application in Expo that can query a Cloudinary account for photos, display thumbnails of all the photos in a nice UI, provide a way to view an image and add a title to it, and search for images based on their title.

## Requirements

1. Fork this repository and issue a pull request with your submission.
2. The application must be built in React Native using [Expo](https://docs.expo.dev/)
3. The application must be built using TypeScript
4. There are no restrictions on any 3rd party plugins or modules you feel would be helpful
5. There is no need for a backend to this application. Any edits or changes that would normally be persisted to a database should just be done using local storage or something similar. The only changes that need to be persisted are adding and deleting images (which will require Cloudinary API work)
6. The application should work on Andriod and IOS.
7. API keys will be provided.

## Screens and UX

The following screens and features must be included

1. A home page that shows a list of all the images as thumbnails.
2. Each thumbnail should display the "title" of the image, if one has been set.
3. From the home page, a search bar should be available that filters the list of images by their title.
4. On the home page, a button should be available that lets users upload a new image to Clourinary. This should be fully functional, it should make use of the phone's camera, and it should actually upload an image to Cloudinary.
5. Returning to the home page should show the newly created image after it has been uploaded.
6. Clicking a thumbnail will take the user to a new "details" page that shows the original image and gives the user the ability to add an arbitrary title to the image. (again, this should be stored locally, there's no backend to this application).

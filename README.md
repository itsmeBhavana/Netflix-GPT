# NETFLIX GPT

- Create React App
- Configured Tailwind CSS
- Header
- Login Form
- Sign up form

## Features

- Login/Signup page
  - Login/Signup form
  - Will be redirected to browse page once logged in
- Browse Page
  - Header
  - Background movie playing
    - Trailer in the background
    - Movie Title
    - Description
    - Movie Suggestion
    - Movie List \* n
  - Netflix GPT
    - Search bar
    - Movie Suggestions

## Set up Routing in the Project

- npm i -d react-router-dom
- create Route
  - const appRouter=createBrowserRouter([
  - {
  - path: "/",
  - element: <Body/>
  - }])
- Provide Route
  - <RouterProvider router={appRouter} >

## Validations
- Its usually very important to write validations inside the form using external libraries like Formik
- These libraries make the form validations very easy and maintainable.

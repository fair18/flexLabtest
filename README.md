flexLabtest
==========================

<b><i>Using Flex to build a Login and user profile page</i></b>

<b>The application should:</b>

    1. Contain two different Views (Do not use Tabs)

<b>Login View 1:</b>

    1. The name of your application at the top (center this label) 
    2. A panel UI component that is located below the application name
    3. The panel should contain one text input for username, a label associated to the text input and a
“Login” button.

<b>Login Button:</b>
    1. When the login button is clicked the app should call the pushView() method with the appropriate
parameters to load the second view
    2. The value of the text input should be passed to the second view
    
<b>User Profile View 2:</b>

    1. A label with the username from the first view, two buttons (Back button and a Add to List button), a
list and a text input UI component

<b>Back Button:</b>
    1. When clicked, this button will call a function that navigates the user back to the first page
(navigator.popView())

<b>Add to List Button:</b>
    1. When clicked, this button will call a function that grabs the value from the text input and adds the
text to the list

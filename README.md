# KeeperApp
About App.js
This code is a React component that renders a Header, Footer, and CreateArea component. It also renders multiple Note components based on the notes in the state. The App component has two functions: addNote and deleteNote. The addNote function takes in a new note as an argument and adds it to the notes array in the state. The deleteNote function takes in an id as an argument and filters out the note with that id from the notes array in the state.
CreateArea.js => This code is a React component that creates a form for taking notes. It imports React, useState from React, AddIcon from @material-ui/icons/Add, and Fab from @material-ui/core/Fab. The component has two states: isExpanded and note. The handleChange function updates the note state with the name and value of the event target. The submitNote function calls onAdd with the note state as an argument and then sets the note state back to an empty object. The expand function sets isExpanded to true when the textarea is clicked on. Finally, it renders a form with an input field if isExpanded is true, a textarea with one or three rows depending on if it's expanded or not, and a Fab button with an AddIcon that calls submitNote when clicked on.
Note>js =>The code starts by importing the DeleteIcon from "@material-ui/icons/Delete" and then creating a function called Note.
The handleClick() function is passed in as an argument to the onDelete() method which will be executed when the button is clicked.
This returns a div with two children, one for the title and another for content of note.
The code creates a new component with the name Note, which is then exported.
The handleClick function will be called when the button is clicked on and it will call props.onDelete(props.id); The code above imports two components: DeleteIcon from "@material-ui/icons/Delete" and Note from "react".
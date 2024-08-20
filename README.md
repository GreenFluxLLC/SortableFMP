# SortableFMP
Drag-and-Drop Sortable List in a FileMaker Web Viewer

This app demonstrates how to create a drag-and-drop list in a FileMaker Pro web viewer using the [SortableJS](https://sortablejs.github.io/Sortable/) library. Dragging to reorder rows in the web viewer updates the `order` column for all rows in the found set using the _Replace Field Content_ step to avoid looping. 
![2024-08-19 07 47 42](https://github.com/user-attachments/assets/834dbff3-9a92-479c-a7cf-ab0308395c59)


**NOTE**: This is a proof of concept, not a complete solution. Adjust the `sortableSQL` custom function and the webviewer HTML field as needed to support your use case. 


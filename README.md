# UFOs

## Project Overview
Using JavaScript and HTML, build a table using data stored in a JavaScript array. Create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing. Finally, customize the webpage using Bootstrap, and equip your table with several fully functional filters that will allow users to interact with our visualizations.

Using JavaScript, create a function that saves the element, value, and id of the filter that was changed. Then, create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage must update with the search criteria after pressing "Enter".

## Resources
- Data source: data.js
- Software: JavaScript, HTML and Bootstrap.

## Results
#### How to use the search criteria:

- The code is programed to detect any changes in the search boxes, save those inputs and filter the data. Initially, once the client opens the webpage, the table will load with all the nonfiltered data. 

![image](https://user-images.githubusercontent.com/91766276/150577039-2c7add96-b5ed-4651-85ea-5b9bb2a50cee.png)

- The client can filter the data using only one criteria e.g., typing *"triangle"* in the *"Enter a Shape"* box and pressing *"Enter"*.

![image](https://user-images.githubusercontent.com/91766276/150579783-80fd8c05-4770-4b9f-b960-5c7de33136e1.png)

- The client can also filter by multiple criteria e.g., typing *"circle"* in the *"Enter a Shape"* box, *"ca"* for State, *"el cajon"* for City and pressing *"Enter"*.

![image](https://user-images.githubusercontent.com/91766276/150579223-b17af986-ed66-43f2-b22d-abee490770b9.png)

#### How to remove the filter:

- To remove a filter, the client must delete the input on the filter that he wants to remove and press *"Enter"*. E.g., Following the previous example, here I deleted the *"el cajon"* filter that was in the City criteria.

![image](https://user-images.githubusercontent.com/91766276/150580337-69ffde0b-37ae-4e03-88a1-70c2eda75bb7.png)


## Summary

I found the website very user friendly with functional filters that allow the clients to interact with the table. However, one drawback is that the filters are suitable if the criteria is spelled correctly, meaning it is case sensitive. It might not be always the case where the client inputs the search criteria without using lower case.

I would recommend adding a solution that supports case-insensitivity and partial inputs, this way the filters will work even if the user types *"El cajon"* instead of *"el cajon"*. Achieving this recommendation will enhance the user experience with the functionality of the filters. 

Finally, I would also recommend adding a *"clear"* button on each filter criteria and a *"clear all"* button to remove all filters. This will make the website more user friendly and will avoid any confusion caused on how to remove the filters.




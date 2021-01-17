# UFO Webpage
## Overview
This project is to create a website that holds information of a research on UFO sights accross the United States, including articles and a dynamic table with multiple search options.

## Results
The full table shows up when the site is loaded.

<img width="1674" alt="Screen Shot 2021-01-17 at 12 02 26 PM" src="https://user-images.githubusercontent.com/72593264/104851635-dfb14f00-58bb-11eb-9870-6b675d08bd53.png">

In order to use the filter to perform a search, just input the desired date/word in the appropriate space, as indicated:

<img width="240" alt="Screen Shot 2021-01-17 at 12 04 59 PM" src="https://user-images.githubusercontent.com/72593264/104851698-3ae34180-58bc-11eb-9516-e064071181f3.png">

You can add as many filters as you want: 
- Country: us
- State: ca
- City: el cajon
- Shape: light

The results will be displayed on the table in real time.

<img width="1652" alt="Screen Shot 2021-01-17 at 12 19 19 PM" src="https://user-images.githubusercontent.com/72593264/104852074-3c156e00-58be-11eb-98cc-ba866e3ee5e1.png">

 

## Summary

- One drawback is that the complete table is loaded when the webpage is loaded. It is not elegant, and once more information is added to table, it will only get worse. The table should be blank inittially, and only be displayed after the first filter input.
- One recommendation is for the filter to automatically lower case any input. As of now, if you search for "CA", instead of "ca", no results will come out.
- Another recommendation is that the filter reset button should be closer to the filter fields, not on the navigation bar. It is not efficient having to roll up the screen everytime a new search needs to be made.
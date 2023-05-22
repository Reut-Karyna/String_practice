# String_practice

This code is used to process and display information about highlighted poems. Let's go through each part of the code to understand its functionality:

highlighted_poems: This is a string that contains information about the highlighted poems. Each poem entry is separated by a comma, and within each entry, the title, poet's name, and publication date are separated by colons.

highlighted_poems_list: This line splits the highlighted_poems string into a list of individual poem entries using the comma as the separator.

highlighted_poems_stripped: This list is created to store the stripped version of each poem entry. The loop iterates over each entry in highlighted_poems_list and uses the strip() method to remove any leading or trailing whitespace. The stripped entries are then appended to the highlighted_poems_stripped list.

highlighted_poems_details: This list is created to store the separated details of each poem. The loop iterates over each stripped entry in highlighted_poems_stripped and uses the split() method with ":" as the separator to split each entry into a list of three elements: title, poet, and date. The resulting lists are then appended to the highlighted_poems_details list.

titles, poets, dates: These empty lists are created to store the titles, poets' names, and publication dates of the poems, respectively.

The next loop iterates over each item in highlighted_poems_details and extracts the title, poet, and date from each item. The title is appended to the titles list, the poet's name to the poets list, and the date to the dates list.

Finally, the code uses a for loop and the range() function to iterate over the length of highlighted_poems_details. It retrieves the corresponding title, poet, and date from the titles, poets, and dates lists, respectively, and prints a formatted string that displays the poem's title, poet, and publication date.

In summary, this code takes a string of highlighted poems, separates them into individual entries, extracts the title, poet, and date for each poem, and then prints the information in a formatted way.

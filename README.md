# Get_Next_Line

#### Get Next Line is a project at 42.

Calling your function get_next_line in a loop will then allow you to read the text
available on a file descriptor one line at a time until the EOF.

# Bonus part

To be able to manage multiple file descriptor with your 
get_next_line. For example, if the file descriptors 3, 4 and 5 are accessible for reading, then you can call
get_next_line once on 3, once on 4, once again on 3 then once on 5 etc. without losing the reading thread on each of the descriptors.

# Online_Voting_System
This is online voting system developed using C language 
The main function serves as the entry point and provides a menu for users to interact with the system:

Options:
1: Cast a vote
2: Access the admin panel
3: View election results
4: Exit the program

Functions
get_voter(): Prompts the user to enter a new voter's details and returns a pointer to a new node containing this information.
add_voter(): Adds a new voter to the linked list of voters.
display(): Displays the list of registered voters.
cast_vote(): Allows a registered voter to cast their vote after verifying their Aadhar number and ensuring they haven't already voted.
search(): Searches for a voter by their Aadhar number in the linked list.
verify(): Checks if a voter has already cast their vote and updates their vote-casting status.
winner(): Determines and prints the winner of the election based on the vote counts.

voteService requirements
========================

- Vote an entry “up” or “down”—The service should provide an API call to rate an entry. This call should require a user ID, an entry ID, and whether the vote is up or down . Further , a user should be able to have only a single vote per entry. The user should be able to change a vote from up to down, but the service should make sure the user can’t continually vote the same way on an entry. 
- Get the entry IDs voted on by a user—Given a user ID, the service should return the list of entry IDs that a user has voted up or down. This list should be in date descending order (by when votes were created), and the API should provide a method to retrieve the list with pagination options. 
- Get the vote totals for an entry—Given an entry ID, the service should return the total up and total down votes for an entry. 
- Get the vote totals for a list of entries—Given a list of entry IDs, the service should return the total up and down votes for each entry in the list. 
- Get the vote for an entry and user—Given an entry ID and a user ID, the service should return the vote information for that user and entry. 
- Get the vote information for a list of entries for a user—Given a list of entry IDs and a single user ID, the service should return the vote information for the entries in the list the user has voted on.
- Get the vote totals for a user—Given a user ID, the service should return the total number of entries voted up and down.

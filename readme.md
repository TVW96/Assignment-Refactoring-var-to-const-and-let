# Assignment: Refactoring var to const and let

#### Description:
First issue was that the variables loggedIn, user, and userRole were undefined. Those variables shoudl be defined outside of the checkAccess function for future reference and given a place holder. Second issue is the same issue as the first but with the message variable. The message variable should be defined outside of the checkAcess function for consistency and clarity. Third and last issue is the foro loop at the end. The loop is placed outside of the checkAccess function and is never ran. The loop should be placed in the last branch of the function just above or below the "return accessLevel" line of code. 

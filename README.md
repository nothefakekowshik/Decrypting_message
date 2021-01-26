# Decrypting_message

In the other repo, we saw how i encrypted a message,in this i'll show how is it decrypted.
We iterate through the character array and we subtract the index from ascii value.
Example:
msg="hfnos cvzun"
the first index is 0, so we subtract nothing
the second index is 1, and we subtract 'f-1',we get e
the second index is 2, and we subtract 'n-2',we get l
and if we continue this process, the decrypted message will be "hello world"

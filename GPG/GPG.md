<h1 align = "center"> 
GPG KEYS <img src= "https://res.cloudinary.com/practicaldev/image/fetch/s--J3u02-Q5--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k8jtac4wnevslvio2fce.png" width ="100 px" height="42px">
</h1>

A GPG key is a security key that allows to put a sign in a commit in github, this is done for preventing another person supplant the identity of the author, when the commit is alredy done in the github platform the sign is automatically done with the commit, but when we are going to do a commit in the terminal is necesary some extra steps.
## How to generate a GPG Key?
There are many ways to generate a new GPG, including programs that generates a new key with only pressing a button, however we are going to explain how to generate a key onlye using commands in the git terminal, because this terminal doesn't need extra extensions or programs for being generate, the steps we need to follow are:
1. Write the command ```gpg --full-generate-key```
2. Select the encryption algorithm we want (It is recommended to choose the RSA and RSA algorithm)
3. It will ask us to choose the size of bits that our key will have, being 4096 bits the maximum (It is recommended to choose 4096 bits)
4. After that it will appear a message asking us to select the time that the key is going to be valid (NEVER select, **No expiration date**)
5. Finally we are going to create a password for our key, and the terminal will show us the key generated in the terminal.

Also we can see the GPG keys that we have with the command ```gpg --list-public-keys```


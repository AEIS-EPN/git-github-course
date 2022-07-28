<h1 align = "center"> 
GPG KEYS <img src= "https://res.cloudinary.com/practicaldev/image/fetch/s--J3u02-Q5--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k8jtac4wnevslvio2fce.png" width ="100 px" height="42px">
</h1>

A GPG key is a security key that allows to put a sign in a commit in github, this is done for preventing another person supplant the identity of the author, when the commit is alredy done in the github platform the sign is automatically done with the commit, but when we are going to do a commit in the terminal is necesary some extra steps.
<h1 align = "center">
    <img src = "https://media4.giphy.com/media/unQ3IJU2RG7DO/giphy.gif?cid=790b761126f2b2287a1a95503e65b24ac5298164dbe5c33b&rid=giphy.gif&ct=g" width = " 200 px" height = " 200 px">
</h1>

---
## How to generate a GPG Key?
There are many ways to generate a new GPG, including programs that generates a new key with only pressing a button, however we are going to explain how to generate a key onlye using commands in the git terminal, because this terminal doesn't need extra extensions or programs for being generate, the steps we need to follow are:
1. Write the command ```gpg --full-generate-key```
2. Select the encryption algorithm we want (It is recommended to choose the RSA and RSA algorithm)
3. It will ask us to choose the size of bits that our key will have, being 4096 bits the maximum (It is recommended to choose 4096 bits)
4. After that it will appear a message asking us to select the time that the key is going to be valid (NEVER select, **No expiration date**)
5. Finally we are going to create a password for our key, and the terminal will show us the key generated in the terminal.

Also we can see the GPG keys that we have with the command ```gpg --list-public-keys```
<h1 align = "center">
    <img src = "https://c.tenor.com/zw6xPc2NxcQAAAAM/confusedanime.gif" width = " 200 px" height = " 175 px">
</h1>


---
## Extra information
In this part we are going to explain how to resolve some problems, that maybe happen when we use terminal to make this changes. First if we need help with the commands that involve a GPG we can write ```gpg --help```, this will list all the commands available for the GPG keys.

If we want to see the keys we had created we can do these:
- ```gpg --list-secret-keys``` (see all the GPG KEYS)
- ```gpg --list-secret-keys``` --keyid-format=long (also see al the GPG KEYS, but adding the full id of them)

If we are going to do all the changes in our IDE or the terminal, we need to configure our key, because without it, all the commits we do aren't going to be sign, this includes if we alredy had put our GPG key in github. We can add this by putting ```git commit -S -m "docs(authors):  add my name title"```, this is just an example, but the extra thing we need to put is the "**-S**" before the rest, if we are having problems with the first command, we can just use instead ```git config --global user.signingkey```, this allow us to auto sign all the commits we do.

Finally, if you want to see more information about this theme you can click the image below, it will open a tab to the oficcial page of GnuPg.
<p align="center">
    <a target="_blank" href="https://www.gnupg.org/documentation/manpage.html">
    <img alt="GnuPg page" src="https://wallpaperaccess.com/full/1619054.jpg" width = " 415 px" height = " 260 px" >
    </a>
</p>




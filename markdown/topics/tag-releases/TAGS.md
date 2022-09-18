<h1 align = 'center'> TAGS </h1>
<p align = 'center'>
    <img src='https://www.w3docs.com/uploads/media/default/0001/03/9e254ef336fa8a35fec2a1305e8ce2ade4337dd3.png' width = '200px'>
</p>

<h3>Contents</h3>

- What's a tag?
- Comands
- Video
- Conclusions
- Bibliography

---

### What's a tag?

Tags are references that point to specific points in Git's history. Typically, people use this functionality to mark release points (v1.0, v2.0 and so on). A tag is like a branch that doesn't change. Unlike branches, tags, after being created, have no further commit history. Through the command ```git tag``` we can create tags, in an operation that is commonly known as "tagging". It is an operation that has many variants and uses.

<img width = '100%' src='https://s3.ap-south-1.amazonaws.com/s3.studytonight.com/tutorials/uploads/pictures/1623844439-103268.png'>

---

### Create

<p align = 'center'>
    <img width = '150' src = 'https://yazilimkaravani.net/wp-content/uploads/2021/05/git_nasil_kullanilir.png'>
</p>

Git supports two different types of tags: annotated and lightweight tags. 

#### Annotated tags

Annotated tags store additional metadata such as: the tagger's name, email, and date.

To create a new annotated tag, run the following command:

``` git tag -a <tag name> -m "description" ```

#### Lightweight Tags

Lightweight tags are basically "placeholders" for a commit; they're just a name and a pointer to a commit, useful for creating quick links to relevant commits.

To create a new lightweight tag, run the following command:

``` git tag -a <tag name> ```

#### Create a branch from a tag

<img width = '100%' src = 'https://miro.medium.com/max/1228/1*AKSMzPHvnZ80BKZaFNo6jg.png' >

You can also create a branch from a tag and move to that version using teh command ```git checkout -b [name branch] [tag] ```

---

### List of tags

To list the tags stored in a repository, run the following:

``` git tag ```

This command lists the tags in alphabetical order; the order in which they are displayed has no real importance.

You can also search for tags that match a particular pattern running:

``` git tag -l <tagname> ```

<p align = 'center'>
    <img src = 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJILsBQrJHQHHL_2MMQviimYunmM4IxyXqSg&usqp=CAU'>
</p>

---
### Sharing Tags

By default, the ```git push``` command doesn’t transfer tags to remote servers. You will have to explicitly push tags to a shared server after you have created them. This process is just like sharing remote branches — you can run ```git push origin <tagname>```.

Or ``` git push origin --tags ``` if you have a lot of tags that you want to push up at once, you can also use the option ```--tag``` to the git push command . This will transfer all of your tags to the remote server that are not already there.

<p align = 'center'>
        <img width = '250'  src = 'https://docs.github.com/assets/images/help/releases/tags-list.png'>
</p>

---

### Deleting Tags

<p align = 'center'>
    <img  width = '100%' src = 'https://t5w2i5w2.rocketcdn.me/wp-content/uploads/2022/03/deleteremotetag.jpg'>
<p>

To delete a tag on your local repository, you can use ```git tag -d <tagname>```.

Note that this does not remove the tag from any remote servers.

To remove a tag from the remote server, you need to run the following: ```git push origin --delete <tagname> ```

---

### Video

You can see this video for more information.

<p align = 'center'>
     <iframe width = '100%' height = '100%' src="https://www.youtube.com/watch?v=vSsypsDRiMU&ab_channel=TravelsCode" style="border:none;" title="Tags in Git. How to use Gits tags?"></iframe>
</p>

---

### Conclusions

- The tags allow you to specify specific points or commits within a repository that are considered important.
- Tagging is used to create identifying labels with semantic version numbers that correspond to software release cycles.
- The command ```git tag``` is the main driver of a tag: creation, modification and deletion. 

---

### Bibliography
    
<ul>
    <li > Atlassian. (2019). git tag | Atlassian Git Tutorial. Recuperado 7 de agosto de 2022, de <a href = 'https://www.atlassian.com'> https://www.atlassian.com</a>.</li>
    <li > Chacon, S. (2015). Git - Tagging. Git. Recuperado 7 de agosto de 2022, de <a href = 'https://git-scm.com/book/en/v2/Git-Basics-Tagging'>https://git-scm.com/book/en/v2/Git-Basics-Tagging</a>.</li> 
</ul>

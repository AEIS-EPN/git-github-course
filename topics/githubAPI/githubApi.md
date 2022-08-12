<a name="main"></a>
<h1 align="center">GITHUB API </h1>
<img width="100%" height="200px" src="https://blog.red-badger.com/hs-fs/hubfs/Github_Blog%20(1).gif?width=920&name=Github_Blog%20(1).gif">

<i><b>On this pages you are going to know about: </b></i> 


* [What's GITHUB?](#item1)
* [What's an API?](#item2)
* [What's GITHUB API?](#item3)
* [What kind of things we can do with GITHUB API?](#item4)
* [Do you want to know more about GITHUB API?](#item5)
* [Conclutions](#item6)
* [References](#item7)

---

## What's GITHUB?
<img width="100%" height="150" src="https://crowdbotics.ghost.io/content/images/2019/07/github.jpg">

[GitHub](https://github.com/) is a cloud-based service which offers a version control system (VCS) know as [GIT](https://git-scm.com/). This service is one of the most useful development tools. It allows developers from any part of the world collaborate and make changes into the same project, while keeping detailed track of their progress. Do you know more about GitHub? Let's talk about the main features that GitHub provide us:

- Version Control System (VCS): Version control is a system that helps track and manage changes made to a file or set of files. It is used by software engineers to keep track of changes made to the source code and  analyze all changes and revert without repercussions if a mistake is made.
- Create repositories: A repository is the location or path where all the information of a project is stored, such as images, code, folders, documents, etc.
- Branch: The Branch will create an exact copy of our project to test without fear of making mistakes and affecting all the work done.
- Fork: With this option you will be able to create a new project based on one already created, allowing you to make modifications and saving it in your own repository and not in the original repository.

---

<!--  Page 3  -->
## What's an API?

API stands for Application Program Interfaces, which developers use to access web tools or information on the cloud. It allows different cross-platform applications to talk to each other. One of the common examples of it is Google Speech to Text API used when you talk to Google Assistant.

<img width="100%" height="200px" src="https://www.imagar.com/wp-content/uploads/2019/10/queesunapi.png">

---

<!--  Page 4  -->

## What's GITHUB API?

<img width="100%" height="200px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSb7wxsrRnnNtHEmY44caQWNl-Fob71cHuLuDj21GwHdtp2xUQYGKn5_pIH_1LL8qzqFno&usqp=CAU">

Github APIs( or Github ReST APIs) are the APIs that you can use to interact with GitHub. They allow you to create and manage repositories, branches, issues, pull requests, and many more. For fetching publicly available information (like public repositories, user profiles, etc.), you can call the API. For other actions, you need to provide an authenticated token.

---

<!--  Page 5  -->

## What kind of things we can do with GITHUB API?

1.- Know information about a specific user: 
```
https://api.github.com/users/{user_name}
```

<img width="100%" height="100%" src="https://www.loginradius.com/blog/static/c9f56c8e81c084bad243f45322340f26/e5715/user_details.png">

---
## What kind of things we can do with GITHUB API?

2.- Fetching user's followers:
```
https://api.github.com/users/{user_name}/followers
```

<img width="100%" height="100%" src="https://www.loginradius.com/blog/static/3298cd5d67ff8492417a65b6b7067d82/e5715/followers.png">

---
## What kind of things we can do with GITHUB API?

3.- Performing tasks as an authenticated user (1/5):

To perform several Github tasks, you must be authenticated. To make it possible, you are expected to create a personal acces token on Github plataform.  To create one, you have to visit developer settings on your GitHub profile settings and create "New personal access token" with the scope and expiration that you need. 

<img width="100%" height="100%"  src="https://docs.github.com/assets/cb-285885/images/personal_token.png">

---
## What kind of things we can do with GITHUB API?

3.- Performing tasks as an authenticated user (2/5):

Then of it, you are able to : 

 - Create a repository: 
```
- curl -H "Authorization: token ${token}" -d '{"name":"Github 
API Testing"}' https://api.github.com/user/repos
```

<img width="100%" height="100%"  src="https://www.loginradius.com/blog/static/40d3976b856cb7dd39bb99f5993cdad9/e5715/create_repo.png">

---
## What kind of things we can do with GITHUB API?

3.- Performing tasks as an authenticated user (3/5):
- List issues assigned to you: 

```
- curl -H "Authorization: token ${token}" 
https://api.github.com/issues
```

<img width="100%" height="100%"  src="https://www.loginradius.com/blog/static/85d67a193b02e71dc4a7642ebde9eac7/5f4af/list_issues.png">

---
## What kind of things we can do with GITHUB API?

3.- Performing tasks as an authenticated user (4/5):

- Creating an issue: 

```
- curl -H "Authorization: token ${token}" -d '{"title":
"Issue_For_Test"}' 
https://api.github.com/repos/devkapilbansal/Github-API-Testing/issues
```

<img width="100%" height="100%" src="https://www.loginradius.com/blog/static/de5adf93eab6a28c28e3efaf2a582fdf/e5715/create_issue.png">

--- 

## What kind of things we can do with GITHUB API?

3.- Performing tasks as an authenticated user (5/5):

There are some possibilities you have with GitHub API. Do you want to know more? Visit the oficial documentation of GitHub API on [Getting started with the REST API](https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api)

---

<!--  Page 6  -->
## Do you want to know more about GITHUB API?

- Introduction to GitHub API: 
<iframe width="100%" height="400" src="https://www.youtube.com/embed/OvfLavRD1Os" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

<!--  Page 7  -->

## Conclutions

-  [GitHub](https://github.com/) is a cloud-based service which offers a version control system (VCS) know as [GIT](https://git-scm.com/).  

- API stands for Application Program Interfaces, which developers use to access web tools or information on the cloud.

- Github APIs( or Github ReST APIs) are the APIs that you can use to interact with GitHub. They allow you to create and manage repositories, branches, issues, pull requests, and many more.

- The best way to know about GitHub API is playing with it 🤓.

<div align="center"><img width="300" height="280" src="https://cdn.memegenerator.es/descargar/18248092">
</div>

---

<!--  Page 8  -->
## References

- Docs, GitHub. Getting started with the REST API. https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api.

- Bansal, Kapil. Introduction to Github APIs. loginradius. https://www.loginradius.com/blog/engineering/github-api/.

- B, Gustavo. ¿Qué es GitHub y Cómo Usarlo? Hostinger Tutoriales. 07 de 22 de 2022. https://www.hostinger.es/tutoriales/que-es-github.




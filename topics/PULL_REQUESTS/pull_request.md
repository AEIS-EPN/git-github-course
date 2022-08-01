<hr>

<img align="left" width="90px" alt="EPN Logo" src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Escudo_de_la_Escuela_Polit%C3%A9cnica_Nacional.png"/>

<img align="right" width="100px" alt="FIS Logo" src="https://fis.epn.edu.ec/images/logo-FIS-sin-fondo.png"/>

<h2 align= "center">
  PULL REQUEST 
  <br>
  <br>
  <br>
  
  <img src = "https://www.campusmvp.es/recursos/image.axd?picture=/2017/2T/in-case-of-fire-git-push.png" width = " 350 px" height = " 330 px">

</h2>


</h1>

A pull request – also referred to as a merge request – is an event that takes place in software development when a contributor/developer is ready to begin the process of merging new code changes with the main project repository.

For example, a user named Harry forked a ThanoshanMV repository and made some changes to it. Now Harry can make a ThanoshanMV pull request, but he saw that ThanoshanMV accepted or declined. It's like saying, "ThanoshanMV, could you please pull my changes?"

<h1 align = "center">
  
  <img src="https://backlog.com/app/themes/backlog-child/assets/img/guides/git/collaboration/pull_requests_001.png" width="600" height="200px">

</h1>

---

## How do Pull Requests Work?

A pull request works by allowing developers to create new features or squash bugs without affecting the main project code or what the users are seeing. This way, they are able to write and test code changes locally without having to worry about breaking the overall product.

Pull requests follow a basic five step process:

- Fork Main Repository and Create a Local Clone. First, the developer creates a fork of the main repository, and then clones this onto their local machine.

- Make Needed Changes Locally. The developer then is able to make their needed changes or additions to the code whether they are working on resolving an issue or new feature.

- Push Local Changes to Forked Repository. Once the developer has completed and tested the new code changes, they push these changes back to the forked repository they created in step one.

- Make a Pull Request. This is where the actual pull request takes place! After requesting a pull request, the main repository maintainer is alerted for review. The maintainer will then review the work done in the developer’s forked repository, and then make any comments or request any edits that need to be made for approval.

- Any edits are then sent back to the developer for additional commits (changes to code) that may be needed.

- If no edits are needed, the pull request is approved by the maintainer.

- Merge with Main Project. Once the repository maintainer has approved a pull request, the developer’s new updates in the forked repository are merged with the main project repository. The product is then updated with the new feature or bug fix, and can now be viewed by end users.


In some cases, a developer may also make a pull request for a feature or update that is not yet completed. This way, if a developer is stuck on a new update they’ve been working on, they can now get feedback from other team members and work through possible solutions.

In either case, using pull requests ensures that any new update for a given project has been thoroughly reviewed and approved before it is merged with the main repository. This helps to prevent future issues and ensures a seamless user experience with minimal downtime.

---

## Creating a Pull Request


Creating pull requests may vary from organization to organization based on the tools being used and the type of repository (ex: GitHub, BitBucket, etc.). However, creating a pull request often involves these same three elements:

### Drafting

When creating a pull request, the developer will first begin with a draft. Here, they will be able to title and briefly describe their code changes. They will need to include information about the type of update (whether it’s a new feature or a bug fix) as well as its source repository/branch and destination repository/branch.

A draft pull request cannot be merged until the developer has marked it as ready for review.

### Merging

Merging occurs once a developer’s submitted pull request has been approved by the repository maintainer. Before merging, the repository maintainer will need to review the developer’s completed work. They will comment on any issues, and request edits from the developer as needed. Once any and all updates have been made, the repository maintainer can then safely merge the updates with the main project repository, making it live for end users.

### Updating

If the repository maintainer requires any changes to the code updates before merging, the developer will be alerted and provided with any comments or feedback for fixing the issue. Once the developer has resolved the issue, they can update the pull request with their new commits added for further review and approval.



---

## An Example of a Pull Request


Now that we’ve gone through what a pull request is and how they work, let’s take a look at a possible pull request in action.

Now that we’ve gone through what a pull request is and how they work, let’s take a look at a possible pull request in action.

1. Russell is a developer at a software company that has a mobile application that lets users rate and review different wines.

2. Russell needs to create a new feature that allows the user to highlight their “Five Favorite Wines”

3. To begin working on this new feature, Russell first creates a fork of the main repository and clones this to his local machine.

4. Russell then develops this new feature locally.

5. Once completed, Russell can push his code updates to the forked repository he created.

6. Now Russell can create a pull request!

7. Once the pull request has been submitted, Erica (the Repository Maintainer) is alerted to begin reviewing Russell’s new code update.

8. Erica can then request any follow-up commits from Russell as needed.

9. When any and all change requests are made, Erica will then approve Russell’s pull request.

10. Russell’s new update is then merged with the main project repository, and application users can now begin using the new application feature.
# Send PR directly on Github

1. Fork the repository: forking a repository creates a copy of the repository on your accoount. This allows you to freely experiment changes without affecting the main repository.

![fork](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/9f09425a-f873-4263-a0e5-160884d63d7a)

After clicking the fork button in the image above, you'll complete the forking process by clicking the create fork button

![fork 1](https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti-DSN/assets/53593233/241c5e54-3fa3-4a86-8ef1-507ff981214e)


2. Create a branch of yours to make your contributions: creating a branch allows you to separate your changes from the main branch which can later be added to the main branch if there is no error or conflict. Else, discarded.

![add branch](https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti-DSN/assets/53593233/ef559823-5e24-4b99-a682-fab3bb937708)

Input the name of your branch and then click "Create branch: branch-name" slightly below the branch name input area

3. When you are done creating the branch, you can start making your contributions.

![make changes](https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti-DSN/assets/53593233/dbb719cb-6e2c-4882-8255-be67806be2e7)


4. When you're done making your contribution, compare & pull request

![compare pull](https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti-DSN/assets/53593233/4d17899c-7f49-43a1-8063-22cc5418caec)

5. Finally, send your pull request.
   You can also leave a comment to explain your contribution.

![pull request](https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti-DSN/assets/53593233/31976c0e-c43f-4bdd-a71d-ba7200372e50)

# Send PR with git

1. Fork the repository as in the first step above

2. Clone the forked repository to your local machine

```markdown
git clone https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti.git
```

3. Navigate to the cloned directory

```markdown
cd Hacktoberfest2023-Ekiti
```

4. Create a branch

```markdown
git checkout -b branch_name (Creates and switches to the new branch created)
```

5. Make your contributions

6. Add, commit and push changes

```markdown
git add file_name (use . to add every files and folders in the directory)
git commit -m 'commit message'
git push origin branch_name
```

If you are having any dificulty, check this article: [https://codesandbox.io/post/how-to-make-your-first-open-source-contribution](https://codesandbox.io/post/how-to-make-your-first-open-source-contribution)

# SKE Project Collection
A curated list of projects collected from the members of Secret Order that uploaded their project to Github.

The project directory is split into an order of, `Year > Semester`

Each of the `Semester` folders has a `README.md` file contained to include the list of projects along with their respective authors.

## Adding Your Project
- Fork this project and clone it onto your machine. Do not work on the main repo!
```sh
> git clone <your_fork_repo> ske-projs
> cd ske-projs
```
- You may or not, make a new branch for your contribution. (Optional)
```sh
ske-projs/ > git checkout -B <your_new_branch>
```
- Navigate to the respective folders and contribute a new submodule there,
for example if your project is in year 1 semester 1,
```sh
ske-projs/ > git submodule add <your_project_repo_on_github> year1/semester1/<repo_name>
```
or if your project is in year 3 semester 2,
```sh
ske-projs/ > git submodule add <your_project_repo_on_github> year3/semester2/<repo_name>
```
- Edit the `README.md` file in that folder to include your project name and the author(s) of that project.
- Finally, make a commit then make a pull request.
```sh
> git add .
> git commit -m "added project by <your_name> to Year 1 Semester 1"
```

## Guidelines on PR Submission
- A pull request will need to come from a member of the organization, any other exterior individuals' PRs are ignored and rejected.
- A pull request should include a new `submodule` linked to a project repository **and** changes to the `README.md` files in respective folders.
- A pull request should be a single commit with a message of whom the project was added and its respective year and semester for example,
```sh
> git commit -m "added project by <your_name> to Year 1 Semester 1"
```
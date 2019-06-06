# How to submit on neurolibre ?

### Python

1. Create a public repository on github which will hold the files
2. Write a notebook `.ipynb` containing all your work
3. Add a requirement file containing all your dependencies
4. Add a data_requirement file containing the data dependencies if needed.
5. Go to https://binder.conp.cloud.
6. Fill the repository name and save the given URL. This will be used to share your binder notebooks with others.
7. Click on upload and wait for the build.
8. If your notebooks are working, you are ready to publish on the neurolibre website! Just make a pull request to fork your repo on https://github.com/neurolibre
 
#### Data
Getting your data on neurolibre is still in development, please try light data. If you have troubles or you want to push your own data, please post an issue.

# TO DO
* Continuous build using circle ci to trigger a push on neurolibre organization
* Automatic build from notebook to jupyter book
* Cookie cutter template for the user

#### Example
https://github.com/ltetrel/binder-tuto
https://github.com/ltetrel/repo2data-caching-s3

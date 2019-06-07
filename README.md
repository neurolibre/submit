# What is NeuroLibre?

NeuroLibre is a curated repository of interactive neuroscience notebooks, seamlessly integrating data, text, code and figures. Notebooks can be freely modified and re-executed through the web, offering a fully reproducible, “libre” path from data to figures. NeuroLibre is powered by the Binder project with computational resources provided by [CONP](http://conp.ca/), [CBRAIN](http://mcin.ca/technology/cbrain/), and [Compute Canada]().

# What can be published on NeuroLibre?

NeuroLibre currently welcomes submissions along two tracks:
 - **Tutorial** notebooks related to a workshop in the neuroscience field.
 - **Companion** notebooks for articles posted as preprints in the neuroscience field.
These workshops notebooks are typically expected to use less than 100 GB, and run in less of an hour, although exceptions may be granted on a case by case basis. 

# How are NeuroLibre submissions reviewed?

Submissions are not reviewed in the sense of a traditional peer-reviewed publication. The NeuroLibre team does check that the notebooks run correctly, and also checks how much compute time and data storage are required. They also check that the submission fits one of the two tracks above. NeuroLibre commits to provide computational resources for free, yet this investment needs to benefit the Open NeuroScience community. The NeuroLibre team reserves the right of rejecting a submission if the content of the notebook is judged to fall outside Neuroscience, requires excessive resources for the proposed scope of work, or is of obvious insufficient quality.

# How to submit?

1. Create a public repository on github which will hold the files
2. Write a notebook `.ipynb` containing all your work
3. Add a requirement file containing all your dependencies
4. Add a data_requirement file containing the data dependencies if needed.
5. Go to https://binder.conp.cloud.
6. Fill in the repository name and save the given URL. This will be used to share your binder notebooks with others.
7. Click on upload and wait for the build. If your notebooks are working, you are ready to publish on the NeuroLibre website!
8. Create an issue on this repository, using the "submission" template, and fill in all the information. 
9. Our team will fork your repository on https://github.com/neurolibre. We will test that everything is working, and contact you using your github handle for any issue we identify. The issues will be open on our fork of the repo, and you will be expected to submit a pull request to this fork to address any issue.
10. Once all issues have been addressed, the repository will be published on the [NeuroLibre website](http://neurolibre.conp.ca), and associated with a unique URL that can be shared publicly.
 
# Examples of NeuroLibre-ready repositories
 * https://github.com/ltetrel/binder-tuto
 * https://github.com/ltetrel/repo2data-caching-s3

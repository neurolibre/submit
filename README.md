<img align="left" src="https://conp-pcno.github.io/images/neurolibre-icon-red.png"> NeuroLibre is a curated repository of interactive neuroscience notebooks, seamlessly integrating data, text, code and figures. Notebooks can be freely modified and re-executed through the web, offering a fully reproducible, “libre” path from data to figures. NeuroLibre is powered by the Binder project with computational resources provided by [CONP](http://conp.ca/), [CBRAIN](http://mcin.ca/technology/cbrain/), and [Compute Canada](https://www.computecanada.ca/).
 
**WARNING:** NeuroLibre is at an alpha stage of development. Our submission and review process is under construction, and the production servers are still not functioning at normal capacity. Please be patient, or come back in a few months for the first stable release of the platform.

# What can be published on NeuroLibre?

NeuroLibre currently welcomes submissions along two tracks:
 - **Tutorial** notebooks related to a workshop in the neuroscience field.
 - **Companion** notebooks for articles posted as preprints in the neuroscience field.
These workshops notebooks are typically expected to use less than 100 GB, and run in less of an hour, although exceptions may be granted on a case by case basis. 

# How are NeuroLibre submissions reviewed?

Submissions are not reviewed in the sense of a traditional peer-reviewed publication, but notebooks do undergo a technical review. The NeuroLibre team checks that the notebooks fit one of the two tracks above, run correctly, and that the text and code are readable. We also check how much compute time and data storage are required. NeuroLibre commits to provide computational resources for free, yet this investment must benefit substantially the Open NeuroScience community. The Neurolibre team reserves the right of rejecting a submission if the content of the notebook is judged to fall outside Neuroscience, requires excessive resources for the proposed scope of work, or if the code or text is of unsufficient quality. Note that NeuroLibre purely reviews the technical aspects of the notebooks, and not the scientific content. As such, a NeuroLibre review complements, rather than replaces, the reviews offered by traditional scientific journals.

# How to submit?

1. Create a public repository on github which will hold the files
2. Write a notebook `.ipynb` containing all your work
3. Create a `binder` folder which will contain all the dependencies :
> * A [requirement file](https://mybinder.readthedocs.io/en/latest/config_files.html#requirements-txt-install-a-python-environment) containing all your dependencies
> * A [data_requirement](https://github.com/SIMEXP/Repo2Data) file containing the data dependencies if needed.
4. Go to https://binder.conp.cloud.
5. Fill the repository name and save the given URL. This will be used to share your binder notebooks with others.
6. Click on `launch` and wait for the build. If your notebooks are working, you are ready to publish on the neurolibre website!
7. [Create an issue](https://github.com/neurolibre/submit/issues/new?assignees=pbellec&labels=&template=submission.md&title=%5BSUBMISSION%5D) on this repository, using the "submission" template, and fill in all the information. 
8. Our team will fork your repository on https://github.com/neurolibre. We will test that everything is working, and contact you using your github handle for any issue we identify. The issues will be open on our fork of the repo, and you will be expected to submit pull request to this fork to address any issue.
9. Once all issues have been addressed, the repository will be published on [NeuroLibre website](http://neurolibre.conp.ca), and associated with a unique URL that can be shared publically.
 
# Examples of NeuroLibre-ready repositories
 * https://github.com/ltetrel/binder-tuto
 * https://github.com/ltetrel/repo2data-caching-s3

# Digital Audio Coding Notebooks

Context: [Digital Audio Coding][audio] course (Mines ParisTech/S1916)

[audio]: https://eul.ink/audio

[![Launch Binder][binder-badge]][audio-binder]

[binder-badge]: https://img.shields.io/badge/Launch-Binder-blue.svg?style=flat-square
[audio-binder]: https://mybinder.org/v2/gh/boisgera/audio-notebooks/master



[Binder] provides an environment to execute the [Jupyter notebooks][jupyter] stored in this
GitHub repository.  With Binder:

[jupyter]: http://jupyter.org/

  - **You can't break anything (no matter how hard you try).**  
    Each Binder session starts with a fresh copy of the files in this repository.  
    

  - **You must download your notebooks to save your work.**  
    Open the `File` menu then select `Download as` and  `Notebook (.ipynb)`.  
    You can also download any file, not merely notebooks, 
    from the "filesystem view"; you can also upload files in this view.

    This step is necessary since all your changes are lost when you close your browser.
    Also, the "disk" button (`Save and Checkpoint`) won't work
    (well, it kinda does but only to save your notebook
    in a [Linux container] hosted "somewhere in the cloud" and 
    that will be destroyed shortly.)

To work without Binder, you need a Linux computer with [conda] available. 
Download the project files and execute:

    $ conda env create -f environment.yml   # create the 'audio' environment
    $ source activate audio                 # activate the 'audio' environment
    (audio) $ jupyter notebook              # start the jupyter server


[Binder]: https://mybinder.org/
[Linux container]: https://en.wikipedia.org/wiki/Linux_containers
[conda]: https://conda.io/docs/

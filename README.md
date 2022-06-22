# DHA2021 Presentation

Joshua Wilson Black
<joshua.black@canterbury.ac.nz>
<joshua@wilsonblack.nz>

This repository contains files for a presentation delivered to the DHA2021
conference (Ka Renarena Te Taukaea | Creating Communities) in November 2021.

A video of the session in which the presentation was delivered is available
[here](https://www.youtube.com/watch?v=w6bWVoe7A20&t=105s).

The presentation is a RISE presentation within a Jupyter notebook. The code
is used to set up a sample of the labelling dashboard with some data from
the Papers Past archive.

I recommend running all cells in the notebook before starting the presentation.

Repository contains:
- `data`:
    - sample items from the Papers Past archive. The data has been
        preprocessed to select only the text for each item (without any information
        concerning, e.g., where it appears on the page). All items in this sample
        will have some match for 'philoso*' (i.e. '_philoso_pher', '_philoso_phy'
        etc).
    - `codes2names.pickle` & `codes2names_web.pickle`: dictionary associating
        newspaper full names with their codes.
- `images`: contains images referred to in the presentation.
- `environment.yml`: contains conda environment information to use by Binder.
- `DH2021_Presentation.ipynb`: Jupyter notebook containing the presentation.

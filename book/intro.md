# 🥳 Welcome to the EGU22 PyGMT short course

This Jupyter book contains [PyGMT](https://www.pygmt.org/v0.6.1) tutorials
for producing maps and doing geospatial data processing 🌍

````{panels}
:column: col-3 align-items-center p-2
:body: text-center

---
:img-top: ./_build/html/_images/first-figure_49_0.png
```{link-button} first-figure
:text: Anatomy of a PyGMT figure
:type: ref
```
by [Leonardo Uieda](https://orcid.org/0000-0001-6123-9515)

---
:img-top: ./_build/html/_images/ecosystem_13_1.png
```{link-button} ecosystem
:text: Integration with the scientific Python ecosystem 🐍
:type: ref
```
by [Max Jones](https://orcid.org/0000-0003-0180-8928)

---
:img-top: https://user-images.githubusercontent.com/23487320/168939109-e35c9d85-4b2d-4623-abd8-66ed1148cf21.png
```{link-button} Mars_Maps
:text: Making some Mars maps with PyGMT
:type: ref
```
by [André L. Belém](https://orcid.org/0000-0002-8865-6180)

---
:img-top: ./_build/html/_images/lidar_to_surface_36_0.png
```{link-button} ecosystem
:text: LiDAR Point clouds to 3D surfaces ✨➡️🏔
:type: ref
```
by [Wei Ji Leong](https://orcid.org/0000-0003-2354-1988)

````

Each tutorial is rendered on this website for easy viewing 👀, but they are all
Jupyter notebooks designed to be ran interactively 💫. See the instructions
below on how you can start running the tutorials in no time! 🚀

# 🌠 Quickstart

To run these notebooks in an interactive Jupyter session online,
🖱️ click on the button below to launch on regular
[Binder](https://mybinder.readthedocs.io/en/latest/index.html).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GenericMappingTools/egu22pygmt/main)

Alternatively, you can go to a specific tutorial page, hover over the rocket 🚀
icon on the top right, and click 'Binder'.

# 💻 Running the notebooks locally

If you prefer to run the 🧑‍🏫 tutorials with a local installation of PyGMT, then
follow along! For this EGU22 short course, we recommend creating a virtual
conda environment and installing the 🐍 Python libraries inside.

:::{tip} For users comfortable with using `git`, feel free to ⬇️ download or
clone the repository containing the short course materials directly using
`git clone https://github.com/GenericMappingTools/egu22pygmt.git`
:::

Here's the instructions to install the `egu22pygmt` environment:

1. Ensure that you have the
   [`conda`](https://docs.conda.io/projects/conda/en/latest/user-guide/index.html)
   package manager installed (e.g. via
   [`miniconda`](https://docs.conda.io/en/latest/miniconda.html) or
   [Anaconda](https://www.anaconda.com/products/distribution)).
   You can also use [`mamba`](https://mamba.readthedocs.io/en/latest/installation.html#fresh-install)
   which tends to be a ⚡ faster alternative.

2. Make a folder called 'egu22pygmt'. This will be where you will put all the
   Jupyter notebooks and data files 🗃️ used in the short course.

3. Download a copy of the 'environment.yml' file which contains a 📄 list of
   dependencies required to run the tutorials in this short course. Get it at
   https://github.com/GenericMappingTools/egu22pygmt/blob/main/environment.yml.

4. Run the following commands on the 🧑‍💻 command-line to create the virtual
   environment

    ```bash
    cd /path/to/egu22pygmt
    conda create --name egu22pygmt --file environment.yml
    ```

5. Once the installation is completed 🏁, launch
   [Jupyter Lab](https://jupyterlab.readthedocs.io) as follows:

    ```bash
    conda activate egu22pygmt
    jupyter lab
    ```

   This should open up a page in your default browser. If not, you can click
   and open the 🔗 link that says `http://localhost:8888/lab?token=...` in your
   command-line terminal and this will will take you to the Jupyter Lab page.

6. Download the Jupyter notebook(s) you want to run (e.g.
   https://www.generic-mapping-tools.org/egu22pygmt/first-figure.html) using
   either the download button on the ↗️ top right (select '.ipynb') or from
   GitHub at https://github.com/GenericMappingTools/egu22pygmt/tree/main/book.
   Make sure to put the *.ipynb file(s) inside of the 'egu22pygmt' folder.

7. Open the Jupyter notebook in the left-pane file browser, e.g. by
   🖱️ double-clicking on `first-figure.ipynb`. You are now ready to run through
   the course materials 🎉!

```{note}
If you're intending to use PyGMT in another project outside of this course,
please follow the official installation instructions at
https://www.pygmt.org/latest/install.html
```

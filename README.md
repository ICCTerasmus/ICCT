# Interactive Course for Control Theory

Interactive Course for Control Theory (ICCT) is an online course based on the active learning concept developed within the Erasmus+ Programme of the European Union. The course is available [here](https://icct.riteh.hr/). This repository provides access to the contents of the platform, which are organized in the form of Jupyter notebooks (written in Python).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for your personal use.

### Prerequisites

In order to make everything work, you need to install Python and Jupyter. 

### Installing Python and Jupyter

The easiest way to install both is to install the Anaconda Distribution.
Go to the [Anaconda download page](https://www.anaconda.com/products/individual) and download the installer package for your OS (Windows, MacOS and Linux are supported).
Use the version for Python 3.7 64-bit.

### Setting up the Anaconda environment and running Juypter (using Anaconda prompt/Linux terminal)

In order to have the reuqired Python packages installed, we prepared a configuration file for the Anaconda environment that you should use to have the same setup as the developers of the course.

In order to create this environment, download [icct2.yml](icct2.yml) file to your computer.
Then open Anaconda Prompt (in Windows) or terminal (in Linux), move to the directory where you downloaded the yml file, and run the following command:

```
conda env create --file icct2.yml
```
Then activate the newly created conda environment in the Anaconda Prompt/terminal:

```
conda activate icct2
```
Now you can run Jupyter by using the following command:

```
jupyter notebook
```

### Setting up the Anaconda environment and running Juypter (using Anaconda Navigator)

If you prefer a graphical user interface you can use the application Anaconda Navigator in Windows. If you already have Jupyter up and running, you can skip this step.

In the dropdown list on the top first change the environment from 
```
base (root)
```
to 
```
icct2
``` 
 and then start the Jupyter notebook application by clicking the *Launch* button.
 
### Running the examples

When Jupyter starts the web browser will open displaying the Jupyter main page. The page typically has the following address http://localhost:8888 and it contains a file browser (*Dashboard*). Using *Dashboard* you can browse the files on your computer. 
Download the examples from this repository to your computer and navigate to their location using the *Dashboard*.
If you want to open one of them just click on it and it will open as a new page/tab inside the web browser.

To run the example click *Cell - Run All* in the dropdown menu.

Then you can interact with the example and when you finish click *File - Close and Halt*.

## Built With

* [The Littlest JupyterHub (TLJH)](https://github.com/jupyterhub/the-littlest-jupyterhub#:~:text=The%20Littlest%20JupyterHub%20(TLJH)%20distribution,for%20their%20students%20or%20users.) - The framework used

## Contributing

If you would like to contribute to our project, please contact us. You can find our contact on our [project webpage](https://icct.cafre.unipi.it/).

## Authors

* **University of Ljubljana**
* **University of Rijeka** 
* **Budapest University of Technology and Economics**
* **University of Pisa**


<!--See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.-->

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* An Erasmus+ funded initiative under grant #2018-1-SI01-KA203-047081 (subject: KA2-HE-04/18)
Call: 2018. KA2 - Cooperation for Innovation and the Exchange of Good Practices. KA203 - Strategic Partnerships for higher education.

The European Commission's support for the production of this publication does not constitute an endorsement of the contents, which reflect the views only of the authors, and the Commission cannot be held responsible for any use which may be made of the information contained therein.

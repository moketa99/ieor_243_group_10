# ieor_243_group_10


Here are some instructions on how to set everything up on your local machine. Everyone should have both git and conda installed already so that shouldn't be an issue. 

### Cloning the Repository

In order to use the codebase locally, you need to clone the repository. To do this, open your terminal and navigate to where you want the project to be. For me, I ran `cd desktop/school/spring-2023` on my terminal.

Then, run `git clone https://github.com/bennettcolecohen/ieor_243_group_10.git` and a bunch of stuff should start downloading. 

Run `ieor_243_group_10` to actually go into the folder containing all the code. 

### Creating a Conda Virtual Environment
In order to run this code, you need to have all the requirements installed. A good practice is to use a virtual environment, which is a way to have an environment in your computer that only contains the packages you need and nothing else. Usually, you can create virtual environments using pip, but because we want to run jupyter notebooks, i recommend creating a conda virtual environment. 

To do this run `conda create --name ieor243` then it will prompt you with a y/n box and type `y` then hit enter.

Now run `conda activate ieor243`. You need to do this everytime you want to use this environment.

Run `conda install pip` to use pip within your environment. Finally, run `pip install -r requirements.txt` and it will install all the packages from the requirements file. 

To open jupyter, run `jupyter notebook` and click enter. Then you should be good!

Anytime you want to use this later, just use terminal cd to get to the directory you want. For me, I run `cd desktop/school/spring-2023/ieor_243_group_10`, then activate your conda environment `conda activate ieor243` and then open a jupyter notebook `jupyter notebook`

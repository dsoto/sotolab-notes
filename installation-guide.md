Lake Sentani Quick Start Guide

1. Create a GitHub account.

2. Create Dropbox account and download the data. Keep it somewhere near
your repository that you set up.

3. Have email invitation sent from HipChat administrator to get into communication channel.

4. Download a GitHub Graphical Client (optional)

5. Fork repositories in dsoto that you want to contribute to: (optional)

	[sentani-codebook](https://github.com/dsoto/sentani-codebook)

6. Create your own sentani-labbook repository. This is where you will
work on your own labbooks. NOTE: If you need help with
this step that is normal and you should contact someone who has done
this before (like Professor Soto or Sean).

	[Create A Repository](https://help.github.com/articles/create-a-repo/)

7. Download Miniconda Mac OS X installation script.

	[Click here to do so.](https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh)

8. Navigate to folder in which the download is located using Terminal.
Enter the following command

		chmod 777 Miniconda3-latest-MacOSX-x86_64.sh

9. Now run the script with the following command

		./Miniconda3-latest-MacOSX-x86_64.sh

10. Exit Terminal and reopen it.

11. Create your first conda environment named sentani

		create -n sotolab -c sotolab pysentani matplotlib bokeh ipython-notebook xlrd seaborn numpy pandas python=3.4

12. Accept the installation. Read an article or watch a funny video while it installs.

13. Your conda environment is intended to manage dependencies and keep
all collaborators utilizing the same packages.
Whenever you work on research, it is intended that you utilize the conda
environment. Activate it with this command from
Terminal.

		source activate sotolab

14. If it activates correctly, you will see (sentani) to the left of
your command prompt. You are now ready. Type the following
command to begin using ipython-notebooks.

		ipython-notebook

15. A kernel will begin in the terminal window and a webpage will open
that represents your local machine's directory structure. Create new
notebooks by pressing New and clicking Python 3.4.

16. Load the data using pandas. See an example of this in any labbook or
codebook currently existent on GitHub.


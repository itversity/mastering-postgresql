# mastering-postgresql
Content related to Mastering Postgresql along with videos.

Here are the steps to contribute for this project.
* Clone the repository
* Create Python virtual environment - `python3 -m venv itvm-env`
* Activate the environment - `source itvm-env/bin/activate`
* Run these commands to install all the dependencies to create jupyter books based up on Python Notebooks.
```shell
pip install jupyterlab
pip install jupyter_book
pip install ghp-import
```
* You can go to the directory which contain files such as _toc.
* Build the book using `jb build .`. As part of the build process, it will generate static HTML files based up on the content.
* Publish the book to GitHub pages using `ghp-import -n -p -c postgresql.itversity.com -f _build/html`
  * `-n` to ensure that jekyll is not used.
  * `-c` is for specifying custom domain for the GitHub based static website that is generated.

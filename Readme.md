# HuPBA Knowledge Base webpage

This is the HuPBA Knowledge base project. The intention of this webpage is to be a source of knowledge for the HuPBA team. It contains all the seminars done from 2021 as well as other resources. The application has been written using the [Curvenote](https://github.com/curvenote) project.

## Installing curvenote and running locally

You need to full install the ``curvenote`` software to see the webpage locally. To do that, you can follow [these instructions](https://curvenote.com/docs/cli/installing). Then, you only need to go to the ``src`` folder and execute ``curvenote start``.

## Adding content to this page. 

This is a collaborative effort so the more content is added, the better is for the team. All new resources are written using the extended Markdown syntax [MYST](https://curvenote.com/blog/working-locally-with-myst-markdown) or Jupyter Notebooks. All the content can be found in the folder ``src/content`` as Markdown ``md`` files or Jupyter Notebook ``ipynb`` files. Inside this ``src/content`` folder, every subfolder containing ``md`` or ``ipynb`` files is considered a category, so keep this in mind when adding your article. Images of your articles are added also in the ``src/content`` directory and we recommend to create a folder ``images`` in every ''category'' folder to store the images associated to your articles. Feel free to propose any change to this main repository to update the website. In the future, accepted pull requests will automatically deploy the website.

To add a new seminar page, you can find the file ``src/content/seminars/seminar-example.md`` where a general structure for your seminar pages is proposed.

In any case, this project is under development and further changes will be added. If there is a bug, contact with me directly in the email rballeba@gmail.com


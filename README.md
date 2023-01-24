# CLionEpitech
This repository contains CLion' settings to use by Epitech students in their projects.

It contains two things:
* The Epitech' *Code Style* for auto formating of the code, which has to be imported in CLion.
* The *standard header* used on top of all files that need to be manually configured.

See below for instructions.

## Code Style

CLion allows you to automatically reformat your code to match the Epitech coding style by using **Code | Reformat Code**
(`CTRL + ALT + L`).
To do so, you need to import the code style in the IDE.

* Download the `Epitech Code Style.xml` file in this repo.
* Open CLion settings (go to **File | Settings**).
* Go to Code Style section (**Editor | Code Style**).
* On the top of the Code Style page you'll find a **Scheme** drop down, with a button next to it. Click on it and select **Import Scheme...**.
* Select the code style on your disk.

## Standard headers

To generate the standard headers on top of all new C/C++ files, you need to set it manually in CLion' settings.

* Open CLion settings (go to **File | Settings**).
* Go to File and Code Templates settings page (**Editor | File and Code Templates**).
* In the tab **Includes**, replace the content of the pre-created **C File Header** by the following code:

```
#if ($HEADER_COMMENTS)
/*
** EPITECH PROJECT, ${YEAR}
** ${PROJECT_NAME}
** File description:
** TODO: add description
*/
#end
```

New files should now be created with the school' standard header. A TODO comment highlighted in yellow in CLion is here
to remind you to write the file description.

You can also download Epiheader from the marketplace and press Ctrl-h to generate a complete header.

## Bugs and reports

If there is any incorrect setting in the files provided in this repo, feel free to open an issue or a pull requests
so I can fix it. Thanks!

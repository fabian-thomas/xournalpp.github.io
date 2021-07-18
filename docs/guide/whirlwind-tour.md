This is a quick tutorial for beginners that will demonstrate:

1. How to set up Xournal++ for the first time
2. How to use the basic pen and eraser tools
3. How to select and manipulate objects
4. How to add pages
5. How to save and load files

We assume that the reader has already downloaded and installed Xournal++. If
not, [instructions can be found here](../installation/index.md).

## How Xournal++ works

Xournal++ is a note-taking tool focused on handwritten notes and digital
tablet/stylus input. To this end, notes are stored in files called **Journals**
(`.xopp` format). A journal can be thought of as a collection of pages of
different formats and sizes. The pages themselves contain visual **elements**
such as pen strokes, shapes, images, etc.

To allow users to create, view, and edit journals, Xournal++ provides a
graphical application (shown in the image below).


TODO: take a screenshot and annotate it with numbers & rectangles

![Tooltip goes here](main_window.jpg)

The application is divided into the following sections:

1. The **canvas** displays the currently loaded journal and allows the user to
   create, delete, or edit elements.
2. The **toolbars** allow the user to select **tools**, which are used to create
   and modify elements. For example, the **Pen Tool** can be used to draw/write
   strokes. The **Select Object** can be used to move, resize, and scale
   elements. One tool may be designated as the "currently activated tool" at any
   time.
3. The **sidebar** is used to preview parts of the journal, including the pages
   and layers (see the section below). Furthermore, buttons at the bottom of the
   sidebar allow the user to create pages.
4. The **menubar** contains a list of menus that provide access to less
   frequently used features, such as the Preferences window and the Plugin
   Manager.

This is roughly all the information that the reader needs to know to get started
with Xournal++. For example, suppose we want to create a stroke. To do this,
select the Pen Tool with a mouse, and then hold the left mouse button down
across some portion of the canvas.

## First time setup

Due to the wide variety of input devices that exist, the default input device
settings in Xournal++ may not be appropriate for your system. Here, we briefly
highlight the settings that may need to be changed in order for Xournal++ to
work correctly for you. Settings may be changed by accessing the `Edit >
Preferences` button in the menu.

### Input device setup

If you are unable to draw strokes or type characters in the Text Tool, check out
the `Input System` tab. This will list the input devices that Xournal++ detects,
as well as the default device class assigned to each device. If the device class
is incorrect, you can override the device class using the drop down menu to the
right.

For example:
* If you are using a combined wireless USB mouse/keyboard device, you may need
  to switch the input device from `Mouse` or `Keyboard` to `Mouse+Keyboard
  Combo`.
* A stylus may be detected as a mouse, which means that pressure sensitivity
  will not work. To fix this, you may need to override the device as a `Stylus`.

### Temporary tool button bindings

The primary button of each input device will activate the currently selected
tool when pressed. However, each secondary button can be set to temporarily
activate a tool when pressed. For example, the right mouse and middle mouse
buttons are set to the `Eraser` and `Hand` tools by default.

### Stylus

TODO

### Touchscreen

By default, touch motions on touchscreen devices will pan or scroll the canvas.
An alternate mode, called "Touch Drawing", causes touch motions to invoke the
selected tool instead. This allows strokes to be drawn directly with touch
motions.

## Creating your first document

Now that we've set up the default settings, we are ready to start exploring how
Xournal++ might actually be used.

1. The typical workflow begins with creating a new journal or loading an
   existing one. The former can be achieved using the `File > New` menu item,
   and the latter can be done by using one of the `File > Open` options.
2. To create a stroke, select the Pen tool from the toolbar. Hold down your
   stylus or mouse on the screen to initiate a stroke, drag it to make the
   strong, and then lift it to end the stroke. You can change stroke attributes
   such as shape, color, and fill using some of the toggle buttons and drop down
   menus in the toolbar.
3. Add a new page by clicking the ![new
   page](https://raw.githubusercontent.com/xournalpp/xournalpp/master/ui/iconsColor-dark/hicolor/scalable/actions/xopp-page-add.svg)
   icon.
4. Save the journal using `File > Save`.

## Adding and manipulating elements

TODO: tutorial on pen options, different shapes, eraser modes, selecting objects
(w/ object, rectangle, and lasso), how to duplicate/rotate/delete selected
objects, and more.

TODO: we can probably include a "tutorial worksheet" that the user can play with

## Annotating PDF files

TODO: tutorial on how to load PDF files, how to use attached mode PDF, etc.


## Working with layers

TODO

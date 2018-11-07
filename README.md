- nested roles

- Preprocessing

- Correct file includes

- default captions on reusable figures

- code:: none

- line breaks or other markup in table cells

- restructured markdown

- proper only

- THEME, with sane cascading and TYPOGRAPHY
  - Large, easy to read type
  - Auto integrate with fontawesome pro or community
  - Can't copy command prompt or new lines in console

- Arbitrary admonition styling to match existing admonition styles

  .. admonition:: Title of Admonition
     :warning:

  .. admonition:: Title of Admonition
     :note:
     :custom-icon:

  - New admonition directive creation

    .. directive:: prereq
       :style: note
       :icon: fa-icon
       :title: Before You Begin

- :command: and :option: don't seem to work quite right?

- HTML5, especially semantics

- classes on errything

- media embeds

- accessibility (mostly a builder issue)

- spell checking that makes sense for tech writing and code

- term plurals, conjugations, etc.
- cross-ref sections with terms (automatic "for more info" from glossary)
- popup inline definitions

- do something with :dfn:

- downcasing titles :doc:`file-name`~ (or something)


- literate programming

  .. code:: python
     :test:

  .. python:: test

  .. python:: code

  .. python:: example

  .. spec::

  .. req::

- forms

- footnotes


- PLUGIN: Annotated videos
  Code samples or other text appear below a video at timestamps.
  Great for tutorials.

  .. video:: /path/to/video.mp4
     :scroll: OR :replace:

     .. 1:02::

        Content Here.

     .. 2:03::

        Content Here.



EDITOR SUPPORT

 - syntax highlighting

 - IDE search/lint/autocomplete

 - extract and run 

 - run in place?



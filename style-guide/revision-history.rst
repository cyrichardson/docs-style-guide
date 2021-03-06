============================
Style guide revision history
============================

This file summarizes the changes that have been made to the style
guide.

June 8, 2020
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Trademarks**: Updated the :ref:`trademarks` section with the following
  changes requested by the Rackspace Legal Department:

  - Removed bold font from Fanatical Support®.
  - Removed the word *a* from in front of Fanatical Experience™.
  - Added Solving Together™.
  - Added Rackspace Technology™.

April 28, 2020
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Ellipses**: For more clarity, added additional information and examples
  in :ref:`ellipses`.

January 28, 2020
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Multiple-paragraph quotations**: Added the following information:

  - Added information about how to format multiple-paragraph quotations in
    :ref:`citations`.

  - Added a link to the Citations section in :ref:`punctuation` under
    "Quotation marks."

  - Updated the "Quotations" row in the table in :ref:`text-formatting` to
    have links to the Citations and Punctuation sections.

July 18, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- In :ref:`user-interface-guidelines`, added link to Hyperlinks conventions
  that is included in the Helix text conventions documentation.

March 12, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Because of the Rackspace rebranding in March 2019, added the new Rackspace
  tagline, Fanatical Experience™, to all relevant sections, but especially to
  :ref:`trademarks`.

  .. note::

     Mirroring its redoubled efforts to target large-enterprise customers
     more effectively, Rackspace replaced its Fanatical Support tagline with
     the more inclusive tagline, Fanatical Experience. The idea that every
     Racker must take partial ownership and responsibility toward each
     customer outcome continues to form the core ethos of its workplace
     culture.

March 6, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added the :ref:`control-panels-and-portals` section that contains
  guidelines for the capitalization and URLs used in our documentation for
  standard control panels and portals.

March 1, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added the :ref:`prepositions` section that contains
  guidelines for using prepositions in sentences.

February 22, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added the section
  :ref:`How-To article guidelines<how-to-article-guidelines>` that contains
  guidelines for the How-To articles that are published at
  https://support.rackspace.com/. The section duplicates the
  information in the `Style guidelines for contributing content <https://github.com/rackerlabs/rackspace-how-to/blob/master/style-guidelines.md>`_
  that is in the ``rackspace-how-to`` repository.

February 6, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added the section
  :ref:`User interface guidelines<user-interface-guidelines>` that contains
  links to the Helix documentation, and specifically to the user interface
  (UI) text conventions in that documentation.

January 21, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added the words *such as* to the alphabetical list of words with examples of
  its use with and without a comma before it, which indicates a nonrestictive
  versus restrictive clause. Also added information and examples for *such as*
  to :ref:`restrictive clauses<restrictive-clauses>`.

January 4, 2019
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Updated requirements.txt to have ``pyyaml>=4.2b1`` based on security alert.
- Updated links to zip files in "Icons, stencils, and shapes" section.

November 5, 2018
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added :ref:`error-message-guidelines`.
- Updated occurrences of the backslash symbol to be properly escaped
  (double backslash) in order for them to display in :ref:`symbols` and
  :ref:`alphabetical-list-of-terms`.

November 2, 2018
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Updated :ref:`trademarks` to have many more trademarks listed as well as
  links to commonly-used company trademark pages to look up trademarks.

September 25, 2018 (End of Q3 release)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added :ref:`blog-guidelines`.

- Added *username* to alphabetical word list.

  The term *username* was added where *user name* is already listed. Use
  *username* as one word if that is how it appears in a user interface,
  screen, or command that you are documenting.

June 29, 2018 (End of Q2 release)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Added :ref:`use-gender-neutral-pronouns`.

-  Added to the word list including the following words:

   *  *abort*

   *  *access*

   *  *admin*, *administrator*, *administer*, *administrative*

   *  *AM*, *PM*

   *  *Android*

   *  *any time*, *anytime*

   *  *API*, *APIs*

   *  *app*, *application*

   *  *argument*

   *  *at scale*

   *  *drop-down*


May 8, 2018
~~~~~~~~~~~

-  Removed the guideline to use the ``bolditalic`` directive for the
   term *Fanatical Support* in RST files (:ref:`trademarks`). For the first
   mention that is not in a heading, the registered
   trademark symbol (Fanatical Support®) to be consistent with
   marketing documentation.

April 16, 2018
~~~~~~~~~~~~~~

-  Added capitalization guidelines for job titles.
-  Added capitalization guidelines for team names.

June 19, 2017
~~~~~~~~~~~~~

Organizational revision:

-  Rewrote many topics to make the content easier to consume.
-  Reorganized the content to create stand-alone topics.
-  Moved several sections from the writing section to the terminology section.

April 28, 2017
~~~~~~~~~~~~~~

-  Added *road map* and *white paper* to :ref:`alphabetical-list-of-terms`.
-  Added *revert back* > *revert* to :ref:`concise-terms`.
-  Added use of the ``.. code-block:: console`` directive to
   :ref:`text-formatting`.

November 10, 2016
~~~~~~~~~~~~~~~~~

-  Converted the style guide to reStructuredText.
-  :ref:`trademarks`: Added guidelines to show the term *Fanatical Support* in
   bold and italics (using the ``:bolditalic:`` directive in RST) and to show
   a registered trademark symbol on first use.

July 27, 2016
~~~~~~~~~~~~~

-  Updated the README and index files to add Rackspace Private Cloud
   contributors as consumers of the style guide.

-  :ref:`alphabetical-list-of-terms`:

   -  *be sure*: Added guidelines to avoid it and use *ensure* or *verify*
      instead.
   -  *data store*: Changed guidelines from one word to two words.
   -  *dialog*: Added guideline to avoid it, and referred to *dialog box*.

-  :ref:`commas-in-numbers`: Revised to use a comma in five-digit numbers,
   rather than 4-digit numbers, to follow IBM and OpenStack guidelines.

-  :ref:`ellipses`: Added a caveat that writers can include an ellipsis with a
   UI label if omitting it would cause confusion.

-  :ref:`placeholder-variable-text`: Revised guidelines to use ``:samp:``
   directive in RST.

-  :ref:`text-formatting`: Updated guidelines to use RST directives when
   available, and noted style differences between Public and Private Cloud.

   -  Command names: Use monospace for Public, apply the ``:command:``
      directive (bold) for Private.
   -  Directory names, file names, paths: Use bold for Public, monospace
      for Private.
   -  Glossary terms: In RST, apply the ``:term:`` directive.
   -  GUI labels: In RST, apply the ``:guilabel:`` directive.
   -  Keyboard keys: Use bold for Public, monospace for Private.
   -  Menu sequences: In RST, apply the ``:menuselection:`` directive.
   -  Option names: In RST, apply the ``:option:`` directive.
   -  Parameter names: In RST, apply the ``:option:`` directive.

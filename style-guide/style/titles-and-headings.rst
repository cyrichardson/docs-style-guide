.. _titles-and-headings:

===================
Titles and headings
===================

This topic provides guidelines for creating titles and headings in
documentation.

-  `Capitalization <#capitalization>`__
-  `Style and structure <#style-and-structure>`__
-  `Text following titles and
   headings <#text-following-titles-and-headings>`__
-  `Tables of contents <#tables-of-contents>`__

Capitalization
~~~~~~~~~~~~~~

Use *sentence-style* capitalization for most titles and headings,
including article, chapter, table, figure, and example titles, as well
as section and procedure headings.

One exception is guide titles, which use *title-style* capitalization.

.. _sentence-style-capitalization:

Guidelines for sentence-style capitalization
--------------------------------------------

In sentence-style capitalization, you capitalize only the first word of
the title or heading, plus any proper nouns, proper adjectives, and
terms that are always capitalized, such as some acronyms and
abbreviations. If the title includes a colon, capitalize the first word
that follows the colon, regardless of its part of speech.

If the heading includes text from a user interface, the capitalization
of that text must match the capitalization on the interface.

.. list-table::
   :widths: 50 50
   :header-rows: 1

   * - Examples
     -
   * - Preparing a cloud server to be a mail server
     - Can I buy extra IP addresses?
   * - What are cloud servers?
     - What are the PHP configuration limits for Cloud Sites?
   * - Install or upgrade PHP 5.3 for CentOS 5.x
     - How do I install my own PEAR module?
   * - Ubuntu 8.04 LTS (Hardy Heron): Using mod\_python to serve your
       application
     - I live outside the United States. Can I use my foreign credit card to
       pay for my account?
   * - Shopping cart software: The basics
     - Troubleshoot a Vyatta site-to-site VPN connection
   * - Back up your files
     - Differences between IMAP and POP

.. _title-style-capitalization:

Guidelines for title-style capitalization
-----------------------------------------

Title-style capitalization uses initial uppercase letters for the first,
last, and all the significant words in the title.

Capitalize all words in the title except for the following types of
words:

- Articles (*a*, *an*, *the*) unless the article is the first word in the title
  or follows a colon
- Coordinating conjunctions (*and*, *but*, *for*, *nor*, *or*, *yet*, *so*)
  unless the conjunction is the first word in the title
- Prepositions of any length, unless the preposition is the first or the last
  word in the title or is part of a verb phrase
- The word *to* in an infinitive phrase unless to is the first word in the
  title
- Second elements attached by hyphens to prefixes unless they're proper nouns
  or proper adjectives
- Words that always begin with a lowercase letter, such as literal command
  names or certain product or software names

.. list-table::
   :widths: 100
   :header-rows: 1

   * - Examples
   * - Next Generation Cloud Servers Developer Guide
   * - Rackspace Cloud DNS Getting Started Guide
   * - Stand-alone Object Storage Guide
   * - Rackspace Private Cloud powered by VMware Customer Handbook
   * - Cloud Networks Release Notes

Style and structure
~~~~~~~~~~~~~~~~~~~

Use the guidelines in this section to create effective and consistent titles
and headings. The following guidelines apply to all titles and headings;
special considerations for stand-alone articles, product guides, and tables,
figures, and examples follow this list.

- Create succinct, meaningful, descriptive titles and headings, and place the
  most important words first.

- Ensure that each title and heading is unique within a given content set.

- Include articles, prepositions, and punctuation as needed for clarity.
  However, avoid using an article (*a*, *an*, or *the*) as the first word.

- Avoid showing both an abbreviation and its spelled-out term in a title or
  heading. To help control the length of titles and headings, show the
  abbreviation in the title or heading and then define it in the first
  paragraph of the text.

- If you show a literal term (such as a command or option name) in a title or
  heading, follow it with an appropriate noun.

- Don't end a title or heading with a colon or period. If the title or heading
  is in the form of a question, end it with a question mark.

- Don't apply font treatments (bold, italics, or monospace) to text in a title
  or heading.

- Don't include trademark symbols in titles or headings. Show the symbol on the
  first use of the trademark in text.

- Avoid having only a single heading at any level (for example, a single
  subsection in an article or section). If you find that you have a single
  heading at any one level, consider whether you can reorganize the information
  to either eliminate the heading or add a second one at that level.

- Avoid having more than two levels of sections within an article or topic. If
  you use more than two levels of sections, consider whether you can reorganize
  to make the structure flatter.

- Don’t "stack" titles or headings. That is, don’t immediately follow a title
  or heading with another title or heading. Text should always intervene
  between them. Ensure that such text is meaningful. If it is just filler text,
  consider whether you can restructure the content.

- Use a consistent grammatical structure for the titles and headings of
  specific types of content:

  .. list-table::
     :widths: 15 25 30 30
     :header-rows: 1

     * - Type
       - Grammatical structure
       - Stand-alone article examples
       - Product guide examples
     * - Conceptual
       - Any grammatical structure that's appropriate, except a verb, gerund, or
         infinitive
       - Linux distributions

         Best practices for backing up your data
       - Core concepts

         How monitoring works

         Limitations of detaching from Rackspace networks
     * - Step-by-step instructions (a task)
       - An imperative verb

         **Note**: For specific guidelines for headings within tasks, see
         :ref:`tasks`.
       - Identify network interfaces on Linux

         Prepare data disks on servers running Windows

         Set up Mobile Sync for Webmail
       - Sign up for a Rackspace Cloud account

         Authenticate with the nova client
     * - Tutorial or high-level process
       - A gerund
       - Understanding logrotate

         Customizing Apache web logs
       - Working with your first message queue
     * - Reference
       - A plural noun or a noun phrase
       - Permissions matrix for Cloud Networks

         Rackspace Auto Scale glossary
       - Environment variables for the nova and supernova clients

         Restore operations

         cURL command summary
     * - Troubleshooting
       - A grammatical structure that's appropriate for the type of content (a
         troubleshooting topic can contain task, tutorial, concept, or reference
         information)
       - Troubleshoot alarms

         Service troubleshooting on Linux
       - Troubleshooting
     * - FAQ
       - A descriptive noun or noun phrase, followed by *FAQ*
       - Rackspace Cloud Billing FAQ

         Scheduled images FAQ
       - Not applicable

Stand-alone articles
--------------------

In addition to the preceding guidelines, use the following guidelines when
creating titles and headings for stand-alone articles on the Support site or in
other collections of documentation:

- Create article titles that don’t rely on body text or other titles for their
  meaning (that are, in other words, independent of context). Users should be
  able to tell from a title whether the information in the article is relevant
  to their needs. Avoid ambiguous one-word titles, such as "Overview."

- Don't number titles to indicate their placement in a series of articles.
  Indicate the order of articles within the content of the article, referring
  users to information that they should have read previously before reading the
  current article. Use links to provide navigation to preceding and following
  articles in the series.

- Start with the highest level of heading that is approved for headings
  (for example, h3), and do not skip heading levels.

Product guides
--------------

In addition to the preceding guidelines, use the following guidelines when
creating titles and headings for sections in product guides:

- If possible, limit titles and headings to 60 characters for legibility in the
  TOC pane.

- Consider that titles and headings are written within the context of the
  content set in which they are presented. Therefore, you can usually omit
  "context-setting" terms. For example, if the content set is about servers,
  you can usually omit "for servers" from the title or heading.
  (For example, "Attach a network to a server" can be shortened to
  "Attach a network" with no loss of clarity.)

- Define consistent heading levels, and do not skip levels.

Tables, figures, and examples
-----------------------------

As a general rule, tables, figures, and examples should have titles
(also called captions). However, tables, figures, and examples in
procedures and tutorials don't normally require titles.

In addition to the preceding guidelines, use the following guidelines when
creating titles for tables, figures, and examples:

-  Place the title above the table, figure, or example, not below it.

-  Tag the title as bold.

-  Avoid using a title that duplicates an article or section title.

Text following titles and headings
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Don’t immediately follow a title or heading with another title or heading.
Instead, follow a title or heading with body text.

The body text must be independent from the title or heading. Don't use a title
or heading as an antecedent in the sentence that follows it. That is, be sure
to repeat the subject in the first sentence that follows the title or heading,
rather than using a pronoun that refers to the title or heading as its
antecedent.

.. list-table::
   :widths: 50 50
   :header-rows: 1

   * - Use
     - Don't use
   * - **Identify network interfaces on Linux**

       This article briefly describes how to identify which network interfaces
       on a Linux server are associated with which IP addresses.
     - **Identify network interfaces on Linux**

       This article briefly describes how to do this.

Tables of contents
~~~~~~~~~~~~~~~~~~

In addition to using the preceding guidelines when creating titles and
headings, use the following guidelines when creating a table of
contents (TOC) for a collection of content:

-  Entries in the TOC should link only to sections in the content. Don't
   include a link to an outside resource in the TOC.

-  The text of a TOC entry must match the text of the title or heading
   to which it links. If the link needs to be shorter, revise the
   title or heading to be shorter.

-  Don't manually format the TOC. TOC formatting must be consistent and
   controlled by the code.

# Notes on markup languages

## Markdown

Markup languages are sets of codes, embodied in tags, that are used to analyze the contents of textual documents. They are also used to contain metadata about works and artifacts. More recently other formats, particularly JSON (JavaScript Object Notation), have become popular because they are more suited to data description.

## SGML

SGML (Standard Generalized Markup Language) is a system for defining markup languages. It is a kind of XML (eXtensible Markup Language), which is a more flexible and powerful version of SGML. XML is a kind of JSON, which is a more flexible and powerful version of XML.

## HTML is a kind of markup language

HTML (HyperText Markup Language) is a markup language that is used to create web pages. It is a kind of SGML (Standard Generalized Markup Language).

HTML’s purpose was to standardize the display of the structure of digital publications. HTML did not contain semantic tagging. Remember, structural tagging was concerned with the format of documents, not their content. It was focused on elements like headings, paragraphs, and so on. The need for semantic markup quickly became evident.

The need for semantic markup quickly became evident. If a corpus of six hundred articles was to be styled, HTML could not distinguish an author’s name from a title, an article abstract from the body of the text, and a subtitle from a publisher’s information when they were identified as “H1” or “H2”. Those categories are semantic and their tags identify the content, not just the formal identity of the text. These are very fundamental distinctions, and semantic markup goes much further in practice.

In fact, as will be seen, it becomes very fine-grained and has many “flavors” that have been developed for different disciplines. The standard format in which semantic mark-up is produced is XML and understanding what it does and how it works is essential for digital publishing and research.

As has already been mentioned, markup languages come in many flavors. Geospatial information uses KML, many text-based projects use TEI, and so on. The use of these standards helps projects communicate with each other and share data.

## XML is a kind of markup language

A number of markup languages are commonly used in the humanities. These include XML (Extensible Markup Language), used for identifying semantic content; TEI (the standard of the Text Encoding Initiative); and KML (Keyhole Markup Language), used for geographical data.

XML stands for eXtensible Markup Language.

XML was designed to store and transport data.

XML was designed to be both human- and machine-readable.

example 1

<?xml version="1.0" encoding="UTF-8"?>
<note>
  <to>Tove</to>
  <from>Jani</from>
  <heading>Reminder</heading>
  <body>Don't forget me this weekend!</body>
</note>

example 2:

<?xml version="1.0" encoding="UTF-8"?>
<breakfast_menu>
<food>
    <name>Belgian Waffles</name>
    <price>$5.95</price>
    <description>
   Two of our famous Belgian Waffles with plenty of real maple syrup
   </description>
    <calories>650</calories>
</food>
<food>
    <name>Strawberry Belgian Waffles</name>
    <price>$7.95</price>
    <description>
    Light Belgian waffles covered with strawberries and whipped cream
    </description>
    <calories>900</calories>
</food>
</breakfast_menu>

## Sublime Text

Sublime Text is a text editor that is used to create and edit markup languages.

## Oxygen


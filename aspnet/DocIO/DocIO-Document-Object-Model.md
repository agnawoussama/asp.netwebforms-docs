---
layout: post
title: DocIO-Document-Object-Model
description: docio document object model
platform: aspnet
control: DocIO
documentation: ug
---

# DocIO Document Object Model

This section shows a Document Object Model of DocIO that helps you to interact with a Word document.

## Object Model Structure

The following illustration shows the Class Diagram for Essential DocIO.

![](DocIO-Document-Object-Model_images/DocIO-Document-Object-Model_img1.png)



_Figure_ _11_: _Class Diagram for Essential DocIO_



* WordDocument: This class contains the collection of sections, bookmarks, styles, footnote and endnote.
* WTable: This class contains the collection of rows in the table.
* WTableRow: This class contains the collection of cells in the row.
* WTableCell: This class contains the collection of textbody items such as paragraphs and tables.
* WParagraph: This class contains the collection of paragraph items.
* Bookmarks: This class contains the list of bookmarks (MS Word: Insert->Bookmarks…).
* Styles: This class contains the list of document styles.
* Sections: This class contains the collection of sections (every section is a region with its own PageSetup options and HeaderFooters).
* TextBodyItem: This class is the base class for container elements of a document such as paragraphs and tables.
* ParagraphItem: This class has elements that contain paragraphs such as formatted text, pictures, special symbols, bookmark markers, fields and so on.

This section gives you a basic introduction to the concepts you need to know before getting started with the product, and some tips and ideas on how to implement DocIO in your projects. Each category under this section explains about the various DLS entities of DocIO.


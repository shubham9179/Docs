---
generator: Adobe RoboHelp 2022
rh-authors: Shubham
rh-index-keywords: Power Grid
robots:
- noindex, nofollow
- noindex, nofollow
title: Power Grid
topic-status: Draft
---

# Power Grid

## In this article 

1.  [Overview](#1)
2.  [Components in Power Grid](#2)
    1.  [Spreedsheet](#2.1)
    2.  [Workbooktab](#2.2)
    3.  [Ribbon Menu](#2.3)
3.  [Actions Performed in the Power Grid](#3)
    1.  [Creating Bids](#3.1)
    2.  [Reviewing Entries](#3.2)
    3.  [Saving Workbook](#3.3)
    4.  [Executing Template](#3.4)

## Overview {#1}

The **Power Grid** module features a spreadsheet-style interface for
managing and validating meter group data, which is crucial for market
submissions. It allows you to input, simulate, and submit energy data
while integrating seamlessly with tools like **Offer Strategy and Bulk
Submit**. Designed for efficiency and accuracy, it supports structured
workflows from data entry to validation and submission, making it a key
component in power market operations.

 

![](../assets/images/Power%20Grid/Overview.png){height="336"
style="border-left-color: #E9E9E9;border-top-color: #E9E9E9;border-right-color: #E9E9E9;border-bottom-color: #E9E9E9;border-left-style: solid;border-top-style: solid;border-right-style: solid;border-bottom-style: solid;border-left-width: 0.2px;border-top-width: 0.2px;border-right-width: 0.2px;border-bottom-width: 0.2px"
width="811"}

------------------------------------------------------------------------

 

## Components in Power Grid {#2}

The components in the Power Grid screen are the interactive elements
that support the creation, validation, and management of generation
offers and demand bids. These include the ribbon menu for selecting
[ISO](#){.glossterm glossterm="ISO"}, participant, date, template
settings, and the spreadsheet grid where you input offer data.

The following are the main components.

1.  **Spreadsheet**
2.  **Workbook Tabs**
3.  **Ribbon Menu**

![](../assets/images/Power%20Grid/Components.png){height="479"
style="border-width: 0.2px; border-style: solid; border-color: rgb(233, 233, 233);"
width="612"}

### a. Spreadsheet Grid {#2.1}

The **Spreadsheet component** in the **Power Grid** screen serves as the
central, Excel-like grid where you can enter, view, and manage bid or
meter data. This primary data entry area, structured with rows and
columns like Excel, is primarily used for inputting, reviewing, and
validating generation offers and demand bids. It supports essential
functionalities such as copy and paste, formulas, filtering, and
formatting, making it a versatile tool for efficient data management.

![](../assets/images/Power%20Grid/Spreedsheet.png){height="281"
style="border-width: 0.2px; border-style: solid; border-color: rgb(233, 233, 233);"
width="774"}

### b. Workbook Tabs  {#2.2}

The **Workbook Tab** in the **Power Grid** screen refers to the section
where you can select, load, or manage bid workbooks tied to a specific
[ISO](#){.glossterm glossterm="ISO"}, participant, and operating date.
It allows you to create a new workbook using a selected template group
or load an existing one for review and editing. This tab ensures the
correct structure and historical context are applied to generation
offers or demand bids, supporting accurate data entry and submission
readiness.

![](../assets/images/Power%20Grid/Workbook%20tab.png){height="160"
style="cursor: nwse-resize;border-left-style: solid;border-left-color: #E9E9E9;border-top-style: solid;border-top-color: #E9E9E9;border-right-style: solid;border-right-color: #E9E9E9;border-bottom-style: solid;border-bottom-color: #E9E9E9;border-left-width: 0.2px;border-top-width: 0.2px;border-right-width: 0.2px;border-bottom-width: 0.2px"
width="770"}

 

 

### c. Ribbon Menu {#2.3}

In the **Power Grid**  you will typically find several key tabs across
the top ribbon, each offering a specific set of tools to manage and
process meter group data. It provides essential tools for configuring,
entering, managing, and validating bid and meter data. It is organized
into several tabs, each offering specific functionalities to streamline
the offer preparation process

![](../assets/images/Power%20Grid/Ribbon%20menu.png){height="198"
style="border-width: 0.2px;border-style: solid;border-color: rgb(233, 233, 233);border-left-width: 0.2px;border-left-style: solid;border-left-color: #E9E9E9;border-top-width: 0.2px;border-top-style: solid;border-top-color: #E9E9E9;border-right-width: 0.2px;border-right-style: solid;border-right-color: #E9E9E9;border-bottom-width: 0.2px;border-bottom-style: solid;border-bottom-color: #E9E9E9"
width="544"}

Here is a detailed explanation for each tab of the **Ribbon Menu**.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**File**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Manage saving, printing, and document properties.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**Home**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Offers basic clipboard and formatting tools.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**Insert**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                    [[[Allows adding rows, columns, and optional controls.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**Formulas**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                  [[[Enables calculation and logic functions within cells.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**Data**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Provides sorting, filtering, and data validation options.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  [[[**View**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Controls layout visibility, zoom, and pane freezing.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 

#### File

The  **File tab**  provides essential options to manage your data sheet,
including saving, printing, and reviewing document details. These
functions are beneficial when preparing offer data, meter groups, or
simulation files for submission or internal review.

Refer to the following specifications for group functionalities in the
**File Tab**.

![](../assets/images/Power%20Grid/File.png){height="138" width="378"}

1.  #### Common

      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Save As**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[It opens a dialog to save the current worksheet locally or on a network drive.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Quick Print**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Sends the document directly to the default printer without confirmation.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Print**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                     [[[Offers advanced print settings (e.g., choose printer, range, layout).]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Print Preview**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Shows how the sheet will appear when printed, allowing you to check formatting.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Undo/Redo**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                 [[[Undo (enabled after change); Redo (greyed out unless Undo is used).]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    #### 

2.  #### Info

      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Document Properties**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                       [[[Displays author, creation/modification time, and document details.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.  #### Clipboard

      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Paste**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                     [[[Inserts content from the clipboard into the selected cell.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Cut**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                       [[[Moves the selected content to the clipboard.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Copy**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Copies of the selected content are uploaded to the clipboard.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Paste Special**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Offers advanced paste functions, such as values-only or transpose.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Home

The **Home tab**  is split into several functional groups to help with
template setup, workbook management, data styling, editing, and
interaction.

![](../assets/images/Power%20Grid/Home%20tab.png){height="113"
width="854"}

Refer to the following specifications for group functionalities in the
**Home Tab**.

 

1.  **Bid Template Workbook**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**[ISO](#){.glossterm glossterm="ISO"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                      [[[Select the target [ISO](#){.glossterm glossterm="ISO"} market.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Participant**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Select the market participant or entity submitting bids.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Template Group**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                            [[[Choose a group of templates for formatting or structural requirements.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Operating Date**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                            [[[Set the date for the workbook's operating window.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                  [[[Select an existing workbook to load or process.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Execute Template**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                          [[[Load the predefined structure or rules for the selected workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Refresh**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Reloads the view or templates without resetting selections.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Load Worksheet**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                            [[[Load a specific sheet from the selected workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Load Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Load the whole workbook into the view.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Clear Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                            [[[Remove all content from the currently loaded workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Copy Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Duplicate an existing workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Save Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Save changes made within the workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Execute Workbook**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                          [[[Run validations or upload operations based on workbook settings.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Bulk Copy**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                 [[[Allows mass data copying across multiple workbooks or sheets.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
2.  **Number**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Number Formatting**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                         [[[Change the display format of numbers (e.g., currency, percentage, decimal).]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
3.  **Styles**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Conditional** **Formatting**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                [[[Highlights cells based on values.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
4.  **Editing**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**AutoSum**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Quickly calculates totals for selected cells.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Fill**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Auto-fills patterns or values across cells.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Clear**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                     [[[Removes content, formatting, or comments.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Sort & Filter**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Organizes data or filters specific conditions.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Find & Select**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Search and highlight specific entries or variables in the template.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
5.  **Actions and Favorites**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Market Link**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Connects to market portals or external submission systems.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Create Favorite**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                           [[[Save this setup or workbook structure for faster access in the future.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    ****

#### Insert

The **Insert tab** provides tools to enhance your data sheet with visual
elements like charts, tables, and comments, helping you analyze trends
and collaborate more effectively.

![](../assets/images/Power%20Grid/Insert%20Tab.png){height="135"
width="506"}

Refer to the following specifications for group functionalities in the
Insert Tab.

 

1.  **Tables**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**PivotTable**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                [[[Create a pivot table for summarizing large bid or meter datasets.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Table**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                     [[[Insert a structured table with headers and sorting/filtering capabilities.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2.  **Charts**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Column**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                    [[[Displays vertical bar charts for comparing unit offers or prices.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Line**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Shows trends across time intervals.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Pie**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                       [[[Displays proportional breakdowns.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Bar**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                       [[[Horizontal version of the column chart.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Area**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Highlights the cumulative value across intervals.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Scatter**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Plot values against two variables.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Other Charts**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                              [[[A dropdown for accessing advanced or less commonly used chart types.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**New Comment**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Adds a comment to a selected cell for collaboration or notes.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Delete**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                    [[[Removes an existing comment.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Show/Hide Comment**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                         [[[Toggles visibility of a comment without deleting it.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Formulas

The **Formulas tab** provides access to a comprehensive Function Library
for applying calculations, logic, lookups, and auditing tools. This
enables you to derive insights, validate values, and control
recalculations within the worksheet.

![](../assets/images/Power%20Grid/Formulas%20Tab.png){height="127"
width="704"}

Refer to the following specifications for group functionalities in the
**Formulas Tab.**

 

1.  **Function Library**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**AutoSum**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Quickly performs SUM, AVERAGE, COUNT, etc., for selected ranges.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Financial**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                 [[[Functions for interest, depreciation, and loan payments.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Logical**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Includes IF, AND, OR, NOT to [add](#){.glossterm glossterm="Add"} decision logic.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Text**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Manipulate text using LEFT, RIGHT, CONCAT, etc.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Date and Time**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Handle dates/times using NOW, TODAY, EDATE, etc.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Lookup and Reference**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                      [[[Retrieve data with VLOOKUP, HLOOKUP, INDEX, and MATCH.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Math and Trig**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Core math functions like ROUND, SUMPRODUCT, and SIN.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Statistical**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Functions like AVERAGE, MEDIAN, and STDEV.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Engineering**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Specialized engineering functions (e.g., BIN2DEC, CONVERT).]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Cube**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[For OLAP cube data references.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Information**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                               [[[Test cell state (ISBLANK, ISNUMBER, TYPE).]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Compatibility**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Legacy Excel-compatible functions for backward support.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
2.  **Formula Auditing**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Show Formulas**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Displays cell formulas instead of values---great for auditing and troubleshooting.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
3.  **Calculation**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Calculation Options**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                       [[[Toggle between automatic and manual calculations.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Calculate Now**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                             [[[Immediately recalculates the entire workbook.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Calculate Sheet**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                           [[[Recalculates only the active valuable sheet for large workbooks.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    ** **

 

#### Data

The Data tab primarily focuses on organizing, validating, and analysing
your dataset. It offers tools for sorting, filtering, validation, and
grouping, crucial for maintaining data integrity in meter group
calculations or offer preparation.

Refer to the following specifications for group functionalities in the
**Data Tab**.

![](../assets/images/Power%20Grid/Data%20Tab.png){height="149"
style="border-left-style: solid;border-top-style: solid;border-right-style: solid;border-bottom-style: solid;border-left-color: #E9E9E9;border-top-color: #E9E9E9;border-right-color: #E9E9E9;border-bottom-color: #E9E9E9;border-left-width: 0.2px;border-top-width: 0.2px;border-right-width: 0.2px;border-bottom-width: 0.2px"
width="516"}

1.  **Sort and Filter**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Gridlines**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                 [[[Toggles the visibility of gridlines that separate spreadsheet cells. Helps distinguish data layout.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Headings**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                  [[[Toggles the row numbers and column letters. Useful for a clean view during print or presentation.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
2.  **Data Tools**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Zoom Out**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                  [[[Reduces the view scale to display more content.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Zoom In**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                   [[[Increases the zoom level for better visibility of small data.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**100%**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                                      [[[Resets zoom level to default (100%) for a standard view.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    \
    ****
3.  **Outline**
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
      [[[**[[Buttons]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}   [[[**[[Description]{style="color:white"}]{lang="EN-IN" style="font-size:14.0pt"}**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      [[[**Freeze Panes**]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}                                                              [[[This feature locks specific rows or columns in place while scrolling, which is essential for viewing headers with long data tables.]{style="color:#333446"}]{style="font-family:Calibri,sans-serif"}]{style="font-size:12pt"}
      -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    ** **

 

------------------------------------------------------------------------

## Actions performed in the Power Grid  {#3}

The actions to perform in the **Power Grid** are used to configure
[ISO](#){.glossterm glossterm="ISO"}, participant, and operating date
settings, apply a template group, and input offer data into a structured
spreadsheet. Additional actions include using formulas, reviewing
entries, saving workbooks, and submitting data through integrated
workflows, ensuring efficient and compliant bid management.

The following are the key actions you can perform:

-   **Creating Bids**
-   **Reviewing Entries**
-   **Saving Workbook**
-   **Executing template**

 

### Creating Bids  {#3.1}

**Creating bids** refers to entering and structuring generation offers
or demand bids for submission to an energy market operator
([ISO](#){.glossterm glossterm="ISO"}) using a defined format. The goal
is to ensure accurate, [ISO](#){.glossterm glossterm="ISO"}-compliant
data entry for market participation and settlement. The following is the
step-by-step procedure to create a bid:

 

1.  Navigate to the **Power Gri**d screen under the **Bids and Offer**s
    module from the left navigation panel.\
    ![](../assets/images/Power%20Grid/Navigate.png){height="320"
    width="808"}

2.  Locate the Bid Template Workbook section in the Home tab. Set the
    filters to **[ISO](#){.glossterm glossterm="ISO"}, Participant,**
    and **Operating Date.\
    ![](../assets/images/Power%20Grid/Home%20tab%20selection.png){height="131"
    width="359"}**

3.  Select a **Template Group** that defines the column structure.\
    ![](../assets/images/Power%20Grid/Template%20group.png){height="145"
    style="cursor: nesw-resize;" width="398"}\
    \

4.  Enter offer/bid data directly into the spreadsheet grid:

    -Unit Name / [Asset](#){.glossterm glossterm="Asset"} ID

    - Time Interval (Hour Ending)

    -MW Offered

    -Price (\$/MWh)

    -Bid Type

    -Status\
    ![](../assets/images/Power%20Grid/Entry%20in%20Power%20grid.png){height="329"
    width="663"}

    **Use Excel-like functions to:**

    -Copy/paste data

    -Apply formulas (e.g., for price scaling)

    -Apply Conditional Formatting for visual validation

    -Use Data Validation to restrict allowed entries (e.g., numeric
    only)

    -The template ensures all required fields and validation rules are
    enforced.\
    \

5.  Review and validate entries using filters or formatting tools.

6.  **Save** the workbook for submission or further use. Saving the
    workbook becomes a formal bid package.

The **created bid** is visible directly in the spreadsheet grid within
the **Power Grid screen**. You can reopen the saved workbook later from
the Workbook drop down or track it through downstream modules.

------------------------------------------------------------------------

### Reviewing Entries {#3.2}

**Reviewing entries** involves verifying the accuracy, completeness, and
compliance of bid or meter data before submission. This step ensures
data quality and adherence to [ISO](#){.glossterm glossterm="ISO"}
requirements. The following is the step-by-step procedure to review
entries:

 

1.  Click on **Sort & Filter** or **Find & Select** to filter the data
    for review.\
    ![](../assets/images/Power%20Grid/Sort%20filters.png){height="140"
    width="986"}
2.  Validate the data and **save**.

------------------------------------------------------------------------

### Saving Workbook {#3.3}

**Saving a workbook** refers to storing the current bid or meter data
entered in the Adapt B2B interface to preserve progress or finalize
inputs. It also supports version control and prevents data loss during
the bid preparation. The following is the step-by-step procedure to save
a workbook:

 

1.  Click on **Save Workbook** to save the edited version of the
    existing one (the button becomes enabled after changes).\
    ![](../assets/images/Power%20Grid/Save%20workbook.png){height="158"
    width="648"}
2.  To save new entries or backups. Click on **Save As** under the File
    Tab.\
    ![](../assets/images/Power%20Grid/Save%20as.png){height="279"
    width="592"}

------------------------------------------------------------------------

### Executing template {#3.4}

**Executing a template** in the **Power Grid screen** refers to the
process of applying a predefined template group that structures the
spreadsheet layout according to [ISO](#){.glossterm glossterm="ISO"} or
internal requirements.

 

1.  Click **Execute Template** to generate the bid input sheet based on
    selected parameters.\
    ![](../assets/images/Power%20Grid/Execute%20Template.png){height="119"
    width="470"}\
    A grid pops up containing a list of bids.
2.  Select the **Bid** you want to execute. Click on **Execute**.\
    ![](../assets/images/Power%20Grid/Executing%20bid.png){height="321"
    width="734"}
3.  Click **Load Worksheet** or **Load Workbook** to retrieve the
    existing structure or previous data.\
    ![](../assets/images/Power%20Grid/Load%20worksheet.png){height="162"
    width="639"}
4.  Click **Refresh** to ensure all dropdowns and sheet components are
    up to date.\
    ![](../assets/images/Power%20Grid/Refresh.png){height="154"
    width="674"}

 

The latest loaded **Workbook** appears.

 

**NOTE:** Always click Refresh after changing any dropdown selection to
avoid working with outdated or mismatched settings.

 

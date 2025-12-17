---
generator: Adobe RoboHelp 2022
rh-authors: Shubham
rh-index-keywords: Offer Calculator Screen
robots:
- noindex, nofollow
- noindex, nofollow
title: Offer Calculator
topic-status: Draft
---

# Offer Calculator

Use the **Offer Calculator **screen under the **Bids & Offers**
module to execute backend offer strategies by specifying parameters such
as date, [ISO](#){.glossterm glossterm="ISO"}, participant,
[asset](#){.glossterm glossterm="Asset"}, and strategy.\
The calculator runs a stored procedure that performs offer pricing and
validation steps, displaying detailed logs during execution.\
You can monitor progress, review execution history, and troubleshoot any
errors using the integrated log viewer.

## Components in the Offer Calculator

[[[The **Offer Calculator** screen includes a ribbon menu for entering
run parameters, an offer run table for viewing execution details, and a
logs window for step-by-step processing insights. Together, these
components support the execution, validation, and troubleshooting of
generation offer
strategies.]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}

Components in this screen are as follows:

-   [Ribbon Menu](#2.1)
-   [Offer Run Table](#2.2)
-   [Logs Table](#2.3)

![](../assets/images/Offer%20Calculator/Components.png){height="371"
width="705"}

### Ribbon Menu {#2.1}

The **Ribbon Menu** serves as the primary control panel for defining
offer execution parameters and triggering backend calculations.

![](../assets/images/Offer%20Calculator/RibbonMenu.png){style="border-width: 0.2px; border-style: solid; border-color: rgb(233, 233, 233);"}

Refer to the following specifications for group functionalities in the
Ribbon Menu.

+-----------------------------------+-----------------------------------+
| [[                                | [[[**[                            |
| [**[[Buttons]{style="color:white" | [Description]{style="color:white" |
| }]{style="font-size:14.0pt"}**]{s | }]{style="font-size:14.0pt"}**]{s |
| tyle="color:#333446"}]{style="fon | tyle="color:#333446"}]{style="fon |
| t-family:\"Objektiv MK1 Regular\" | t-family:\"Objektiv MK1 Regular\" |
| ,serif"}]{style="font-size:10pt"} | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**From/To**]{s                 | [[[Defines the start and end      |
| tyle="color:#333446"}]{style="fon | dates for the execution window of |
| t-family:\"Objektiv MK1 Regular\" | the offer                         |
| ,serif"}]{style="font-size:10pt"} | strategy.]{s                      |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Start Hour / End             | [[[Specifies the hourly range     |
| Hour**]{s                         | (within the selected date range)  |
| tyle="color:#333446"}]{style="fon | to constrain the calculation      |
| t-family:\"Objektiv MK1 Regular\" | period.]{s                        |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**[ISO](#){.glossterm          | [[[[Selects the target            |
| glossterm="ISO"}**]{s             | [ISO](#){.glossterm               |
| tyle="color:#333446"}]{style="fon | glossterm="ISO"} market in which  |
| t-family:\"Objektiv MK1 Regular\" | the offer will be                 |
| ,serif"}]{style="font-size:10pt"} | submitted.]{lang="EN-AU"          |
|                                   | style="color:#333                 |
|                                   | 446"}[]{style="color:#333446"}]{s |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Participant**]{s             | [[[Identifies the market          |
| tyle="color:#333446"}]{style="fon | participant or bidding            |
| t-family:\"Objektiv MK1 Regular\" | entity.]{s                        |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
|                                   |                                   |
|                                   | [[[**NOTE**: Options are          |
|                                   | dynamically updated based on the  |
|                                   | selected [ISO](#){.glossterm      |
|                                   | glossterm="ISO"}.]{s              |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Group**]{s                   | [[[Designates the                 |
| tyle="color:#333446"}]{style="fon | [asset](#){.glossterm             |
| t-family:\"Objektiv MK1 Regular\" | glossterm="Asset"} group to be    |
| ,serif"}]{style="font-size:10pt"} | used for the selected             |
|                                   | strategy.]{s                      |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Assets**]{s                  | [[[Displays the individual assets |
| tyle="color:#333446"}]{style="fon | associated with the selected      |
| t-family:\"Objektiv MK1 Regular\" | group.]{s                         |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Strategy                     | [[[Filters the available offer    |
| Group**]{s                        | strategies by logical or          |
| tyle="color:#333446"}]{style="fon | operational                       |
| t-family:\"Objektiv MK1 Regular\" | categories.]{s                    |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Strategy**]{s                | [[[Selects the specific strategy  |
| tyle="color:#333446"}]{style="fon | logic to apply during offer       |
| t-family:\"Objektiv MK1 Regular\" | calculation.]{s                   |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Refresh**]{s                 | [[[Reloads the page based on the  |
| tyle="color:#333446"}]{style="fon | configured selections and updates |
| t-family:\"Objektiv MK1 Regular\" | dependent                         |
| ,serif"}]{style="font-size:10pt"} | dropdowns.]{s                     |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Execute**]{s                 | Initiates the offer strategy run  |
| tyle="color:#333446"}]{style="fon | using the configured parameters   |
| t-family:\"Objektiv MK1 Regular\" | and strategy logic.               |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+

**NOTE**: Always click Refresh after changing any input field to ensure
the latest parameter data is loaded.

### Offer Run History Table {##2.2}

The **Offer Run History Table** lists all executed offer strategies,
including their IDs, participants, time ranges, and run results.\
Expanding a row shows the detailed process logs for that execution.

![](../assets/images/Offer%20Calculator/OfferRunHistoryTable.png){height="329"
style="border-style: solid; border-color: rgb(233, 233, 233); border-width: 0.2px;"
width="673"}

Below is a detailed explanation of each column.

+-----------------------------------+-----------------------------------+
| [[                                | [[[**[                            |
| [**[[Buttons]{style="color:white" | [Description]{style="color:white" |
| }]{style="font-size:14.0pt"}**]{s | }]{style="font-size:14.0pt"}**]{s |
| tyle="color:#333446"}]{style="fon | tyle="color:#333446"}]{style="fon |
| t-family:\"Objektiv MK1 Regular\" | t-family:\"Objektiv MK1 Regular\" |
| ,serif"}]{style="font-size:10pt"} | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**[[ID]{style="f               | [[[Specifies the Unique           |
| ont-weight:normal"}]{lang="EN-AU" | identifier for each offer run     |
| style="font-family:\"Ob           | entry.]{s                         |
| jektiv MK1 Regular\",serif"}**]{s | tyle="color:#333446"}]{style="fon |
| tyle="color:#333446"}]{style="fon | t-family:\"Objektiv MK1 Regular\" |
| t-family:\"Objektiv MK1 Regular\" | ,serif"}]{style="font-size:10pt"} |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**Participants**]{s            | Displays the market participant   |
| tyle="color:#333446"}]{style="fon | or bidding entity associated with |
| t-family:\"Objektiv MK1 Regular\" | the run.                          |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**Start                        | Defines the beginning of the      |
| Date**]{s                         | offer calculation window.         |
| tyle="color:#333446"}]{style="fon |                                   |
| t-family:\"Objektiv MK1 Regular\" |                                   |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**End                          | [[[Specifies the end of the offer |
| Date**]{s                         | calculation                       |
| tyle="color:#333446"}]{style="fon | window.]{s                        |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Run                          | [[[Captures the timestamp when    |
| Start**]{s                        | the offer calculation process     |
| tyle="color:#333446"}]{style="fon | begins.]{s                        |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Run                          | [[[Captures the timestamp when    |
| End**]{s                          | the offer calculation process     |
| tyle="color:#333446"}]{style="fon | completes.]{s                     |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[[[Comments]{style="f           | [[[Summarizes the execution       |
| ont-weight:normal"}]{lang="EN-AU" | result or system status           |
| style="font-family:\"             | message.]{s                       |
| Objektiv MK1 Regular\",serif"}]{s | tyle="color:#333446"}]{style="fon |
| tyle="color:#333446"}]{style="fon | t-family:\"Objektiv MK1 Regular\" |
| t-family:\"Objektiv MK1 Regular\" | ,serif"}]{style="font-size:10pt"} |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**Info                         | Indicates the number of           |
| Count[[]{style="f                 | informational messages generated  |
| ont-weight:normal"}]{lang="EN-AU" | during the run.                   |
| style="font-family:\"Ob           |                                   |
| jektiv MK1 Regular\",serif"}**]{s | [[[]{s                            |
| tyle="color:#333446"}]{style="fon | tyle="color:#333446"}]{style="fon |
| t-family:\"Objektiv MK1 Regular\" | t-family:\"Objektiv MK1 Regular\" |
| ,serif"}]{style="font-size:10pt"} | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Error                        | [[[Indicates the number of errors |
| Count**]{s                        | encountered during the offer      |
| tyle="color:#333446"}]{style="fon | calculation                       |
| t-family:\"Objektiv MK1 Regular\" | run.[]{style="display:none"}]{s   |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
|                                   |                                   |
|                                   | [[[]{s                            |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**User**]{s                    | [[[Displays the name of the user  |
| tyle="color:#333446"}]{style="fon | who initiated the offer           |
| t-family:\"Objektiv MK1 Regular\" | calculation                       |
| ,serif"}]{style="font-size:10pt"} | run.]{s                           |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+

**Offer Run History Logs Sub-Table**

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  [[[**[[Field]{style="color:white"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}           [[[**[[Description]{style="color:white"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[ID]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}              [[[[[Link the log entry to its corresponding offer strategy run.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Bill Category]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}   [[[[[Represent the billing category processed (e.g., DA Spot Market).]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Charge Type]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}     [[[[[Specify the type of market charge processed.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Sequence]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}        [[[[[Define the execution order of each calculation step.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Process]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}         [[[[[Identify the internal process executed (e.g., stored procedure, calculation).]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Run Start]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}       [[[[[Record when the individual process began.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Run End]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}         [[[[[Record when the individual process is completed.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  [[[**[[Duration]{style="color:black"}]{style="font-size:11.0pt"}**]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}        [[[[[Measure the elapsed time for the specific process execution.]{style="color:black"}]{style="font-size:11.0pt"}]{style="color:#333446"}]{style="font-family:\"Objektiv MK1 Regular\",serif"}]{style="font-size:10pt"}
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Logs Table {#2.3}

The Logs Table provides detailed execution information for each run,
enabling you to trace processes, verify outcomes, and diagnose any
issues that may arise.

+-----------------------------------+-----------------------------------+
| [[                                | [[[**[                            |
| [**[[Buttons]{style="color:white" | [Description]{style="color:white" |
| }]{style="font-size:14.0pt"}**]{s | }]{style="font-size:14.0pt"}**]{s |
| tyle="color:#333446"}]{style="fon | tyle="color:#333446"}]{style="fon |
| t-family:\"Objektiv MK1 Regular\" | t-family:\"Objektiv MK1 Regular\" |
| ,serif"}]{style="font-size:10pt"} | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**[[ID]{style="f               | [[[Identifies the unique ID for   |
| ont-weight:normal"}]{lang="EN-AU" | the log                           |
| style="font-family:\"Ob           | entry.]{s                         |
| jektiv MK1 Regular\",serif"}**]{s | tyle="color:#333446"}]{style="fon |
| tyle="color:#333446"}]{style="fon | t-family:\"Objektiv MK1 Regular\" |
| t-family:\"Objektiv MK1 Regular\" | ,serif"}]{style="font-size:10pt"} |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**Run                          | [[[References the ID that links   |
| Id**]{s                           | the log entry to a specific offer |
| tyle="color:#333446"}]{style="fon | run.]{s                           |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Strategy**]{s                | [[[Indicates the strategy used    |
| tyle="color:#333446"}]{style="fon | during the offer calculation      |
| t-family:\"Objektiv MK1 Regular\" | step.]{s                          |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Strategy                     | [[[Group strategies by type or    |
| Group**]{s                        | purpose for organizational        |
| tyle="color:#333446"}]{style="fon | reference.]{s                     |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**[Asset](#){.glossterm        | [[[Displays the name of the       |
| glossterm="Asset"}**]{s           | [asset](#){.glossterm             |
| tyle="color:#333446"}]{style="fon | glossterm="Asset"} associated     |
| t-family:\"Objektiv MK1 Regular\" | with the log                      |
| ,serif"}]{style="font-size:10pt"} | entry.]{s                         |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Sequence**]{s                | [[[Shows the step number          |
| tyle="color:#333446"}]{style="fon | representing the execution order  |
| t-family:\"Objektiv MK1 Regular\" | within the                        |
| ,serif"}]{style="font-size:10pt"} | run.]{s                           |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Process**]{s                 | [[[Displays the name of the       |
| tyle="color:#333446"}]{style="fon | process being                     |
| t-family:\"Objektiv MK1 Regular\" | executed.]{s                      |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Run                          | Indicates the timestamp when the  |
| Start[[]{style="f                 | log process began execution.      |
| ont-weight:normal"}]{lang="EN-AU" |                                   |
| style="font-family:\"Ob           |                                   |
| jektiv MK1 Regular\",serif"}**]{s |                                   |
| tyle="color:#333446"}]{style="fon |                                   |
| t-family:\"Objektiv MK1 Regular\" |                                   |
| ,serif"}]{style="font-size:10pt"} |                                   |
+-----------------------------------+-----------------------------------+
| [[[**Run                          | Indicates the timestamp when the  |
| End**]{s                          | log process completed execution.  |
| tyle="color:#333446"}]{style="fon |                                   |
| t-family:\"Objektiv MK1 Regular\" | [[[]{s                            |
| ,serif"}]{style="font-size:10pt"} | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Log                          | [[[Indicates the severity or type |
| Level**]{s                        | of log                            |
| tyle="color:#333446"}]{style="fon | message.]{s                       |
| t-family:\"Objektiv MK1 Regular\" | tyle="color:#333446"}]{style="fon |
| ,serif"}]{style="font-size:10pt"} | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+
| [[[**Comment**]{s                 | [[[Provides a detailed message    |
| tyle="color:#333446"}]{style="fon | related to the process execution  |
| t-family:\"Objektiv MK1 Regular\" | or                                |
| ,serif"}]{style="font-size:10pt"} | error.]{s                         |
|                                   | tyle="color:#333446"}]{style="fon |
|                                   | t-family:\"Objektiv MK1 Regular\" |
|                                   | ,serif"}]{style="font-size:10pt"} |
+-----------------------------------+-----------------------------------+

## Actions to Perform in the Offer Calculator

The **Offer Calculator** screen provides an intuitive interface for
configuring and executing offer strategies by interacting with backend
calculation services. You can review detailed logs to understand the
execution flow, identify errors, and rerun processes if needed. This
functionality supports the creation of accurate and transparent offers
for market submissions.

1.  [Executing Strategy](#3.1)
2.  [Error Handling in Offer Calculator](#3.2)

### Run an Offer Strategy {#3.1}

Use the **Offer Calculator** to execute predefined offer strategies
based on selected parameters such as date, [ISO](#){.glossterm
glossterm="ISO"}, participant, group, and [asset](#){.glossterm
glossterm="Asset"}. The system processes the strategy through stored
procedures, displays real-time logs for each step, and records the run
details in the **Offer Run History** Table for verification or
troubleshooting.

To run an offer strategy, perform the following steps:

1.  Access the **Offer Calculator** screen from the **Bids & Offers**
    module.

2.  In the **Offer Calculator** screen, open the **Ribbon Menu**.\
    ![](../assets/images/Offer%20Calculator/1RibbonMenu.png){height="329"
    style="border-style: solid; border-color: rgb(233, 233, 233); border-width: 0.2px;"
    width="673"}

3.  Set the following fields:

    -   **From / To Date** -- Select the calculation period.

    -   **Start Hour / End Hour** -- Define the time window.

    -   **[ISO](#){.glossterm glossterm="ISO"}** -- Choose the target
        market (for example, PJM or MISO).

    -   **Participant** -- Select the market participant.

    -   **Group** -- Choose the [asset](#){.glossterm glossterm="Asset"}
        group.

    -   **[Asset](#){.glossterm glossterm="Asset"}** -- Select the
        specific [asset](#){.glossterm glossterm="Asset"}.

    -   **Strategy** **Group** -- Choose the appropriate category.

    -   **Strategy** -- Select the offer strategy to execute.

4.  Click **Refresh** to validate the selected parameters and reload any
    dependent fields.\
    ![](../assets/images/Offer%20Calculator/2RefreshButton.png){height="329"
    style="border-width: 0.2px; border-style: solid; border-color: rgb(233, 233, 233);"
    width="673"}

5.  Click **Execute** to start the offer calculation.\
    ![](../assets/images/Offer%20Calculator/3Execute.png){height="103"
    style="border-width: 0.2px; border-style: solid;" width="671"}\
    The system runs the backend stored procedure and displays real-time
    progress in the log viewer.\
    ![](../assets/images/Offer%20Calculator/LogsTable.png){height="103"
    style="border-width: 0.2px; border-style: solid; border-color: rgb(233, 233, 233);"
    width="671"}

6.  After execution completes, close the log viewer.

7.  Click **Refresh** again to update the **Offer Run History** Table.\
    ![](../assets/images/Offer%20Calculator/7RefreshButton.png){height="103"
    style="border-color: rgb(233, 233, 233); border-width: 0.2px; border-style: solid;"
    width="671"}

8.  Click the **Expand (+)** icon beside a run ID to review detailed
    logs.\
    ![](../assets/images/Offer%20Calculator/LogsTableCollapseView.png){height="103"
    style="border-width: 0.2px; border-color: rgb(233, 233, 233); border-style: solid;"
    width="671"}\
    ![](../assets/images/Offer%20Calculator/LogsTableExpandView.png){height="103"
    style="border-style: solid; border-color: rgb(233, 233, 233); border-width: 0.2px;"
    width="671"}

The executed offer strategy appears in the **Offer Run History Table**
with a success or error status.\
All corresponding log entries are accessible for review under the
selected run.

### Error Handling in the Offer Calculator Screen

System-generated errors can occur during the calculation of offers.
After executing a strategy, any errors are displayed in the **Logs**
pop-up window.

Use the following steps to review and resolve them.

1.  In the **Logs** window, hover over the **Comment** column for the
    corresponding row to view the detailed error description.\
    ![](../assets/images/Offer%20Calculator/Error%20Message.gif){height="376"
    style="border-style: solid; border-width: 0.2px; border-color: rgb(233, 233, 233);"
    width="800"}
2.  Record the error details and raise a support ticket, including the
    complete log message for reference.
3.  After the issue is resolved, return to the **Offer Calculator**
    screen.
4.  Re-enter the required parameters in the **Ribbon Menu** and click
    **Execute** to rerun the strategy.

The system re-executes the offer calculation using the corrected
parameters. If successful, the new run appears in the **Offer Run
History** Table with an updated status of **Success** and no error
messages in the log.

**Tip**: If the same error reappears, verify your parameter
configuration or strategy logic before re-executing.

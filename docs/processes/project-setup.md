# Project Setup 

## Smartsheet

### Project Workspace Setup

A consistent location and structure of project assets is required. The following describes the process for generating a standard project workspace in Smartsheet, which includes standard templates for various project management processes and establishes uniform reporting and dashboarding.

**Pre-Requisites**

- A Smartsheet license is required.

**Process**

1. Copy the template workspace named *'xxxx_GTE ProjectWorkspaceTemplate'* in Smartsheet by choosing 'Save as New'.
*Note: To copy a workspace, right click it in the workspace tree and choose 'Save as New'. See the Smartsheet documentation here for more detailed instruction.*
2. Name the workspace according to the template convention, where:
    - 'xxxx' is the Project ID, and
    - 'GTE' should be replaced with the Client's name in pascal case, and
    - 'ProjectWorkspaceTemplate' should be replaced with the project name as it reads in the [Project Register](https://app.smartsheet.com/sheets/cjMrq22wxV6pHhfX2mJMWJpgW2vFxr86hfc2Vrh1) (which should be pascal cased).
*Note: Pascal case should be interpreted as all words capitalised, without spaces, and with underscores used to separate words where the first word ends in a capital (eg SCADA).*
3. When presented with options:
    - Under 'Sharing Options', check 'Sharing'. The templates within the workspace will adopt the appropriate standard collaborators and you can add others later as required.
    - Under 'Automated Workflow & Alert Options', check 'Include recipients & permissions settings'.
    <TODO: What does this actually do? May be worth explaining? Gibbo suggested he knows but didnt elaborate at the time.>
4. Leave the 'Data & Formatting Options' all checked. Some templates are pre-populated with reference data and this ensures those rows will be copied to the new workspace, and forms, shared filters, etc will also be available.
5. Leave 'Newly created sheets' selected.

### Project Schedule Setup

A consistent project schedule structure is required to facilitate team familiarisation and to present uniform to the client for all GTE projects. The GTE standard project schedule also includes reporting calculations required for organization wide analysis.

The project schedule is to be created and managed in Smartsheet. The following outlines the process for generating a standard project schedule in Smartsheet.

**Pre-Requisites**

- A Smartsheet license is required.
- It is assumed the workspace for the project has been created from the project workspace template. If this has not yet been done, first refer to [Project Workspace Setup](#project-workspace-setup).

**Process**

1. Locate the sheet named *'Pxxxx_Schedule [TEMPLATE]'* in the project workspace.

    *Note: If the sheet cannot be located or was deleted, open the project workspace template and  right-click the file of the same name, choose 'Save as New' and save it to the relevant project workspace.*

2. Open the sheet and rename it according to the template convention by clicking the existing sheet name in the header bar, where:
    - 'xxxx' is the Project ID, and 
    - '[TEMPLATE]' should be removed from the name.

3. Open the Sheet Summary and set the 'Project ID' field to the appropriate value (excluding the leading "P").

    *Note: The Sheet Summary can be opened using the summary icon ![Alt](https://help.smartsheet.com/sites/default/files/inline-images/Sheet-Summary-Icon_0.png) on the right menu bar. See the [Smartsheet documentation here for more detailed instruction](https://help.smartsheet.com/learning-track/smartsheet-intermediate/sheet-summary).*

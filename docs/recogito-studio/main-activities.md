# Main Activities

This section provides information on:
- creating a new project,
- adding a new document,
- modifying document's metadata, 
- creating a group,
- annotating TEI texts or PDF documents,
- annotating IIIF, JPG or PNG Images
- installing Geotagger plugin to your project**.

---

## Create a New Project

???+ note "User priviledges"
    To create a new project, you need to have a proper organization role, which means having a `Professor` or `Admin` role. Further information can be found here.

1. [Login to Recogito Studio](account-management.md/#login-to-recogito-studio).

1. Press a **"New Project"** button in the top right corner of the page.

    ![New Project button](main-activities/new-project-button.png)

1. Provide the project name and description, set projects properties, and press the **"Create"** button.

    ???+ note "Project properties - Project Visibility"
        You can select two options in Project Visibility section:

        - **Private** - project is visible only to the admin and users who join after receiving an admin invitation.
        - **Public** - any registered user can access the project by visiting the **"Public Projects"** section.

    ???+ note "Project properties - Project Type"
        You can select two options in Project Type section:

        - **Assignments** - project admins create assignments with specific documents, and team members fulfil the given tasks.
        - **Single Team** - project members can annotate any document.

    ![Create a new project](main-activities/project-creation.png)

1. Upon creating, an empty project page will be displayed. 

    ![Empty project page](main-activities/creation-success.png)

---

## Add New Document

1. [Create](#create-new-project) or open a project.

1. Press the **"Add Document"** button in the top right corner.

    ![Add Document button](main-activities/add-document-button.png)

1. Press the **"Import"** button and select a file from your device or provide a IIIF manifest.

    ![Import Document button](main-activities/import-options.png)

1. (Optional) Go to the **"All documents"** section and select documents of interest from the list of publicly available ones across the organization.

    ![All Documents section](main-activities/public-documents.png)

1. Wait for processing, which ends with a confirmation message and a new document object.

    ???+ note
        To inspect the document from the adding panel, you need to refresh the page by hand.

    ![Import ended with success](main-activities/successful-import.png)
# Main Activities

This section provides information on:
- creating a new project,
- adding a new document,
- modifying document metadata, 
- creating a group,
- annotating TEI texts or PDF documents,
- annotating IIIF, JPG or PNG images,
- installing Geotagger plugin in your project.

---

## Create a New Project

???+ note "User priviledges"
    To create a new project, you need to have a proper organization role, which means having a `Professor` or `Admin` role. Further information can be found [here]().

1. [Login to Recogito Studio](account-management.md/#login-to-recogito-studio).

1. Press the **"New Project"** button in the top right corner of the page.

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

1. Upon creation, an empty project page will be displayed. 

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

---

## Modify Document Metadata

### Method 1

1. Open a project, click the three dots in the object representing the document, and click **"Edit document metadata"**.

    ![Edit document metadata](main-activities/edit-document-metadata.png)

1. Add or modify document's metadata and save the changes.

    ???+ note
        Here, you can also change a name of the file in the Recogito Studio.

    ![Modify metadata](main-activities/modify-metadata.png)

---

### Method 2

1. Open a project, click the "Add Document" button, and click three vertical dots next to the document of interest.

    ![Modify metadata](main-activities/method-2.png)

1. Here you can edit document metadata (see point 2 in **[Method 1](#method-1)**), change its status, or remove it from Recogito Studio.

    ???+ note "Make Public / Make Private"
        This option allows the user to change document accessibility. If status is `Private`, only users inside a specific project can see this document. If status is `Public`, any logged-in user can access this file via the **"All Documents"** section.

---

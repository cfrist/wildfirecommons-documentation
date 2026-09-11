# CollabStudio

CollabStudios are collaborative spaces designed for research groups to develop, organize, and share their work. Within a project, members can create and manage multiple workspaces, allowing them to build complete end-to-end pipelines.

Each group is allocated 5 GB of shared storage on our main JupyterHub service to support their projects. Please review the PVC (Persistent Volume Claim) policy on [this page](../../policies/pvc-policy.md) for important details regarding storage usage and retention.

## Creating a CollabStudio

1 - Go to your Research Hub and click *New CollabStudio*.

2 - Fill in the project creation form, including a title, description, and the participating institution(s).

   <img src="../images/form.png" style="border: 2px solid black;">

3 - If the project is funded, select *Yes* to add lead investigator and funding organization information.

4 - Click *Set up CollabStudio*.

5 - To add new members to your CollabStudio, click *Add a Group*.

6 - Provide a name for your group. Avoid special characters and date formats, since this name will be used to create a shared storage folder in JupyterHub.

   <img src="../images/project-group.png" style="border: 2px solid black;">

7 - Enter the email addresses of the group members. Make sure your collaborators are already registered in Wildfire Commons, or you'll get an error message.

8 - Click *Add Group* to save it. You can edit group membership later if needed, and you can add multiple groups to the same CollabStudio.

9 - Click *Add a Workspace* to add workspaces to the project. Any member of the CollabStudio can contribute workspaces, so the group's tools and pipelines can be built collaboratively.

   <img src="../images/add-workspace.png">

10 - Click *Save Project* to finalize your project setup. You can continue making edits to the CollabStudio at any time after it's created.

Once the project is launched, any member can open it and add additional workspaces or curated catalogs, and can launch the CollabStudio's workspaces in JupyterHub.

## Publishing Your CollabStudio

If you want your CollabStudio to be shared across the broader community as an open resource, click *Publish* in the top right. This creates a public copy of your CollabStudio, which other users can review or copy to work from.
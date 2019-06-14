---
description: Create a new Process to begin your Process modeling.
---

# Create a New Process

## Create a New Process

{% hint style="info" %}
Your user account or group membership must have the following permissions to create a new Process:

* Processes: View Processes
* Processes: Create Processes

See the [Process](../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#processes) permissions or ask your ProcessMaker Administrator for assistance.
{% endhint %}

Follow these steps to create a new Process:

1. [View your active Processes.](./#view-your-processes) The **Processes** page displays.
2. Click the **+Process** button. The **Create Process** screen displays.  

   ![](../../../.gitbook/assets/add-a-process-screen-processes.png)

3. In the **Name** field, enter the name of the Process. This is a required field.
4. In the **Description** field, enter a description of the Process. This is a required field.
5. From the **Category** drop-down, select a category to associate with the Process. This is a required field. See [Process Categories](../process-categories.md) for more information.
6. Optionally, upload a third-party BPMN 2.0 compliant BPMN file from which to use its process model in ProcessMaker. Do not use this function to upload a ProcessMaker 4 `.spark` file. Import that file. See [Import a BPMN-Compliant Process](import-a-bpmn-compliant-process.md).

   To do so, follow these guidelines:

   1. Ensure that the third-party process model is BPMN 2.0 compliant and has the `.BPMN` file extension.
   2. Click the **Upload File** button, and then browse for the third-party `.BPMN` file to use as your process model.

7. Click **Save**. Your new Process opens in Process Modeler. See [Process Modeling](../../process-design/) for topics.

## Related Topics

{% page-ref page="../what-is-a-process.md" %}

{% page-ref page="view-your-processes.md" %}

{% page-ref page="import-a-bpmn-compliant-process.md" %}

{% page-ref page="search-for-a-process.md" %}

{% page-ref page="export-a-bpmn-compliant-process.md" %}

{% page-ref page="../process-categories.md" %}

{% page-ref page="edit-the-name-description-category-or-status-of-a-process.md" %}

{% page-ref page="remove-a-process.md" %}

{% page-ref page="restore-a-process.md" %}

{% page-ref page="../../process-design/model-your-process/" %}



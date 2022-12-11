# project-7(personal project)

Lab 02b - Manage Governance via Azure Policy


Lab scenario
Your organization is piloting a new infrastructure project. The CTO wants to know which Azure resources are being used on the new project. Your specific tasks are:
•	Create a way to tag the project resources.
•	Don't allow resources to be created without the resource tag.
•	If a resource is created without the tag, automatically add the tag.


Objectives
In this lab, we will:

Task 1: Create and assign tags via the Azure portal
Task 2: Enforce tagging via an Azure policy
Task 3: Apply tagging via an Azure policy


details of objectives

Objectives
•	Task 1: Create and assign tags via the Azure portal.
o	For testing purposes, identify the Cloud Shell resource group.
o	Add a tag to the resource group. Assign the value of the tag.
o	Verify the storage account in the resource group doesn't have the tag.
•	Task 2: Enforce tagging by using an Azure policy.
o	Locate the Require a tag and its value on resources built-in policy and review the definition.
o	Assign the policy to the resource group.
o	Configure the required tag: Role with a value of Infra.
o	Create a new storage account in the resource group and verify without the tag you can't create the resource.
•	Task 3: Automatically apply tagging by using an Azure policy.
o	Assign the Inherit a tag from the resource group if missing built-in policy to the resource group.
o	Configure remediation to automatically add the Role tag if it is missing from a new resource.
o	Create a new storage account and verify the tag and value are added.

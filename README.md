# Decomissining-AD-Group

Decomissions an active directory group and deletes it in 5 days.

**What it does:** Decommissioning a group in active Directory

**Purpose:** This script provides ease with decommissioning a group in Active Directory. This helps with decluttering and cleaning up random groups in active directory that are not being used. This script will download a csv file of the group’s group name, members, description, owner etc. Then it will remove all of those specific attributes as well as create a task in the task scheduler to delete the group in 5 days.

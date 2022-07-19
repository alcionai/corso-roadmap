# Corso roadmap

You can see the Corso project roadmap
[here](https://github.com/orgs/alcionai/projects/1/).

## Guide to the roadmap

Every item on the roadmap is an issue, with labels that indicates the following
categories:

* **Workflow Feature Area** - describes the workflow area functionality (e.g.
backup) supported by Corso and represented by a given item. Workflow features
are typically orthogonal to the data type being protected. See below for more
details and list of current labels in this category.  

* **Data Type** - describes the type of data (e.g. Exchange emails) supported
by Corso and represented by a given item. Data type support is typically
orthogonal to the workflows that may use it. See below for more details and
list of current labels in this category.  

* **Priority** - describes the priority of a given item. Priority is often
relative to other items within the same **Workflow Feature Area** or
**DataType**. It is used to express relative ordering of such related items and
slotting into roadmap stages. See details below.  

* **Additional Areas** - describes other areas that can benefit from filtering
(e.g. docs). See below for more details and list of current labels in this
category.  

## Workflow feature areas

The following is a list of feature areas which are currently tracked.  

* **area:install** - Functionality related to Corso installation and packaging.

* **area:storage** - Functionality related to using Corso with different
storage backends and in different storage interaction patterns.  

* **area:backup** - Functionality related to backup workflows.  

* **area:restore** - Functionality related to restore workflows and restore
options.  

* **area:cli** - Functionality related to general Corso CLI.  

## Data Types

The following is a list of data types which are currently tracked.  

* **m365:exchange** - Microsoft Exchange data.  

* **m365:onedrive** - Microsoft OneDrive data.  

* **m365:sharepoint** - Microsoft SharePoint data.

* **m365:teams** - Microsoft Teams data.  

*NOTE:* Initial Corso focus is on Microsoft 365 services.  

## Priorities

Priority is often defined relative to other items within the same
**Workflow Feature Area** or **Data Type**. It is used to express relative
ordering of such related items and slotting into roadmap stages. The following
is the the list of priorities currently used.

* **P0** - Core functionality. Required for introducing new workflow or data
type support.  

* **P1** - Important functionality. Should be considered for inclusion ASAP to
solidify support for new workflow or data type.  

* **P2** - Fit & finish and less frequently used functionality. Consider for
including after **P0** and **P1** items for a given workflow or data type.  

## Roadmap stages

The issue *Status* field is used to indicate the current roadmap timing of
issues. It indicates the best estimate of the expected quarter in which an
item is likely to become available. The timing is advisory as priorities can
and do change during planning cicles. The certainty of the projected timing
decreases further out along the timeline.  

Items which are not yet planned and for which no timeline is available yet are
assigned **Status**=*Future*. Such items are included on the roadmap board in
order to gather additional feedback. There is no guarantee that such items will
be selected for development.

## Released features

When a feature is released, the corresponding item is tagged with label
`released`. Additionally the item is closed as completed and a link is added to the changelog describing the change.  

## Triage process

Issues without an assigned status (**Status**=*No Status*) are still awating triage. For each of these, one of the follwing will happen:  

* *Assign to an upcoming quarter* - Issue is already well understood and fits
with overall Corso project goals.  

* *Move to **Future*** - Issue is interesting for the Corso project but requires
more feedback and research to determine priority and potential timeline.  

* *Close issue as not planned* - Issue is a duplicate, stale, or won't fix
(not aligned with near-term Corso goals).  

Any feature that has not been already released but is assigned to a quarter that has already passed needs to go to the triage process even if the resolution is to push it to a subsequent quarter.  
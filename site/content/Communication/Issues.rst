======
Issues
======

The canonical way of reporting issues should be from the client website. Insert JS for certain IP ranges or user login that allows a bug reporting form.

Things to collect
-----------------

- User Agent
- Device
- Request URI
- Session ID
- Screenshot
- User Feedback
- Time
- HTTP Status code

Automated Reporting
-------------------

Automatically submit report with the following error codes:
   5xx

Prompted Reporting
------------------

Provide a form to submit for any other error codes.

Tracking
--------

Use labels to indicate a ticket status, and a binary ticket state -- "open" being needs attention, and "closed" being "will not be revisited unless it's not resolved".

Labels could be "Needs Triage", "Mitigated", "Needs Rca" etc.

Assigned Labels
"""""""""""""""

=========================== ==========================
Label                       Meaning
--------------------------- --------------------------
Needs triage                Hasn't been looked at yet
=========================== ==========================

Communication
-------------

Preworked responses looks excellent on the Ansible repo. They have a series of common responses when reporting issues, which do well to express our point of view.

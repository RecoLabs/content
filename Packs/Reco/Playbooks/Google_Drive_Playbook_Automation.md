Google Drive Playbook Automation

## Dependencies

This playbook depends on the following integrations:
 - Google Drive
 - Slack

### Sub-playbooks

This playbook depends on the following sub-playbooks:
 - Reco - Revoke Assets

### Integrations

Reco

### Scripts

This playbook does not use any scripts.

### Commands

slack-get-user-details
send-notification

## Playbook Inputs

---

| **Name**                 | **Description**               | **Default Value**         | **Required** |
|--------------------------|-------------------------------| ------------------------- | ------------ |
| Reco  | Finding Json Object from Reco | ${incident} | Required     |

## Playbook Outputs

This playbook does not have any outputs.

## Playbook Image

---

![Armis Alert Enrichment](../doc_files/Google_Drive_Playbook_Automation.png)

# OmniWatch Change History

This repository tracks changes in Microsoft 365 tenant settings with a focus on Power Platform configurations. It serves as a historical record and audit trail for all tenant changes.

## Monitored Categories

1. **Power Platform**
   - Environment settings
   - DLP policies
   - Copilot features
   - AI Builder settings
   - Apps inventory
   - Flow configurations

2. **Service Health & Communications**
   - Service messages
   - Health status
   - Message center updates

3. **Teams**
   - Teams policies
   - App integrations
   - Copilot features
   - External access

4. **SharePoint**
   - Tenant settings
   - Features
   - Site templates

5. **Core Microsoft 365**
   - Directory audit logs
   - Conditional access policies
   - Service principals

## File Structure

Each change is saved as a JSON file with a timestamp in the following format:
`category_subcategory_YYYYMMDD_HHMMSS.json`

## Change Detection

Changes are detected by comparing consecutive snapshots. The comparison looks at:
- Added items
- Removed items
- Modified configurations
- Timestamp of changes
- Change initiator (Microsoft vs. tenant admin) 
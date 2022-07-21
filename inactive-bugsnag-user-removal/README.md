# Audit and Remove Inactive Bugsnag Users in OKTA

## OKTA Workflow Structure


This flopack audits Bugsnag users similar to the template for Auditing Inactive Okta Users

## How to use

- Import bugsnagAuditAndRemoveInactiveUsers.folder into a folder within OKTA Workflows
- Create a connection to Bugsnag using the Custom API Connector
- Change the `$INSERT_GROUP_ID` in the `For each - Bugsnag Inactivity Audit` at the Remove User from Group card to the group you would like to remove users from
- Change the `$INSERT_ORG_ID` in the `Scheduled Start - BugSnag Inactivity Audit` at the Call Flow card to the appropriate organization ID

## Images
- Scheduled Start ![image](https://user-images.githubusercontent.com/3143796/180318356-ef90d76c-7f13-4375-bc24-7dda83ee163b.png)
- List Bugsnag users - Part 1 ![image](https://user-images.githubusercontent.com/3143796/180318663-2c84628f-cb72-4623-858a-53db908c2af4.png)
- List Bugsnag users - Part 2 ![image](https://user-images.githubusercontent.com/3143796/180319389-c2fc8368-9b26-44ea-9911-6d0f5cfd089b.png)
- List Bugsnag users - Part 3 
<br />![image](https://user-images.githubusercontent.com/3143796/180319465-88238b72-a761-4010-9971-237ec453c697.png)
- For each - Bugsnag Inactivity Audit - Part 1 ![image](https://user-images.githubusercontent.com/3143796/180319807-3d0dbe82-04b6-46a0-8acb-1d1542074eba.png)
- For each - Bugsnag Inactivity Audit - Part 2 ![image](https://user-images.githubusercontent.com/3143796/180319871-0f85a3c7-73bf-4efb-ab01-e01948be3e0f.png)
- For each - Bugsnag Inactivity Audit - Part 3 <br />![image](https://user-images.githubusercontent.com/3143796/180320188-ec509ba2-30ea-4c1f-b33a-69be06076844.png))
- Table ![image](https://user-images.githubusercontent.com/3143796/180319985-0377feed-5828-4780-8fe0-8dfbf987ea8b.png))

## Special Thanks

Thanks to the original author of the modified workflow this was based on https://github.com/pro4tlzz/ITSupportTools/blob/main/okta-workflows/inactive-google-workspace-users/README.md
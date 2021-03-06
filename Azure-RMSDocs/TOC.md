# [Overview](/azure/information-protection/what-is-information-protection)
## [What is Azure Information Protection?](what-is-information-protection.md)
## [Comparing Azure Information Protection and AD RMS](compare-on-premise.md)
## [Requirements](requirements.md)
### [Azure Active Directory requirements](requirements-azure-ad.md)
### [Client device support for data protection](requirements-client-devices.md)
### [Application support for data protection](requirements-applications.md)
### [On-premises server support for data protection](requirements-servers.md)

# [Quickstarts](/azure/information-protection/quickstart-viewpolicy)
## [Get started in the Azure portal](quickstart-viewpolicy.md)
## [Find what sensitive information you have](quickstart-findsensitiveinfo.md)
## [Configure a label to protect emails](quickstart-label-dnf-protectedemail.md)
## [Create a new label for specific users](quickstart-label-specificusers.md)

# [Tutorials](infoprotect-quick-start-tutorial.md)
## [Edit the policy and create a new label](infoprotect-quick-start-tutorial.md)
## [Configure policy settings that work together](infoprotect-settings-tutorial.md)
# [Concepts](overview-policy.md)
## [Overview of the Azure Information Protection policy](overview-policy.md)
## [Rights Management protection](what-is-azure-rms.md)
### [How does it work?](how-does-it-work.md)
### [How applications support Azure Rights Management protection](applications-support.md)
#### [Office applications and services](office-apps-services-support.md)
#### [File servers that run Windows Server and use File Classification Infrastructure](file-server-support.md)
#### [RMS sharing application for Windows and mobile platforms](sharing-app-support.md)
#### [Other applications that support the RMS APIs](api-support.md)
## [RMS for individuals and Azure Information Protection](rms-for-individuals.md)
## [Also known as ...](aka.md)

# [How-to guides](how-to-guides.md)
## [How-tos for common scenarios](how-to-guides.md)

# [Resources](faqs.md)
## [Frequently asked questions](faqs.md)
### [FAQs for classification and labeling](faqs-infoprotect.md)
### [FAQs for data protection](faqs-rms.md)
## [Information and support](information-support.md)
### [Fast help](help-bot.md)
## [Compliance and supporting information](compliance.md)
## [PowerShell reference](https://docs.microsoft.com/powershell/azure/aip/overview?view=azureipps)
## [Terminology](terminology.md)

# [Plan & Design](deployment-roadmap.md)
## [Deployment roadmap](deployment-roadmap.md)
## [Migrating from AD RMS](migrate-from-ad-rms-to-azure-rms.md)
### [Preparation](migrate-from-ad-rms-phase1.md)
### [Server-side configuration](migrate-from-ad-rms-phase2.md)
#### [Software key to software key](migrate-softwarekey-to-softwarekey.md)
#### [HSM key to HSM key](migrate-hsmkey-to-hsmkey.md)
#### [Software key to HSM key](migrate-softwarekey-to-hsmkey.md)
### [Client-side configuration](migrate-from-ad-rms-phase3.md)
### [Supporting services configuration](migrate-from-ad-rms-phase4.md)
### [Post migration tasks](migrate-from-ad-rms-phase5.md)
## [Planning and implementing your tenant key](plan-implement-tenant-key.md)
### [BYOK pricing and restrictions](byok-price-restrictions.md)
## [Preparing users and groups](prepare.md)

# [Deploy & Use the Service](activate-service.md)
## [Activating the service](activate-service.md)
### [Office 365 admin center](activate-office365.md)
### [Azure portal](activate-azure.md)
## [Configuring applications](configure-applications.md)
### [Office 365](configure-office365.md)
### [Office apps](configure-office-apps.md)
### [Azure Information Protection client](configure-client.md)
### [RMS sharing app](configure-sharing-app.md)
## [Configuring usage rights](configure-usage-rights.md)
## [Configuring super users for discovery services or data recovery](configure-super-users.md)
## [Configuring the Azure Information Protection policy](configure-policy.md)
### [The default policy](configure-policy-default.md)
### [Configure the policy settings](configure-policy-settings.md)
### [Create a new label](configure-policy-new-label.md)
### [Add or remove a label](configure-policy-add-remove-label.md)
### [Delete or reorder a label](configure-policy-delete-reorder.md)
### [Change a label](configure-policy-change-label.md)
### [Configure protection](configure-policy-protection.md)
#### [HYOK](configure-adrms-restrictions.md)
### [Configure visual markings](configure-policy-markings.md)
### [Configure conditions](configure-policy-classification.md)
### [Configure scoped policies](configure-policy-scope.md)
### [Configure and manage templates](configure-policy-templates.md)
#### [Refresh templates for users](refresh-templates.md)
#### [PowerShell reference](configure-templates-with-powershell.md)
#### [Migrating from the Azure classic portal](migrate-portal.md)
### [Configure languages](configure-policy-languages.md)
### [Migrate labels to Office 365](configure-policy-migrate-labels.md)
## [Configure secure document collaboration](secure-collaboration-documents.md)
## [Configuring mail flow rules for Azure Information Protection labels](configure-exo-rules.md)
## [Deploying the Azure Information Protection scanner](deploy-aip-scanner.md)
## [Reporting for Azure Information Protection](reports-aip.md)
## [Deploying the RMS connector](deploy-rms-connector.md)
### [Install and configure the connector](install-configure-rms-connector.md)
### [Configure servers](configure-servers-rms-connector.md)
#### [Registry settings](rms-connector-registry-settings.md)
### [Monitor the connector](monitor-rms-connector.md)
## [Verifying the Azure Rights Management service](verify.md)
## [Helping users to protect files](help-users.md)
## [Logging and analyzing usage](log-analyze-usage.md)
## [Operations for your tenant key](operations-tenant-key.md)
### [Microsoft-managed](operations-microsoft-managed-tenant-key.md)
### [Customer-managed](operations-customer-managed-tenant-key.md)
## [Manage personal data for Azure Information Protection](manage-personal-data.md)
## [Decommissioning and deactivating](decommission-deactivate.md)
## [Administering with PowerShell](administer-powershell.md)
### [Installing the AADRM PowerShell module](install-powershell.md)

# [Deploy & Use the Client](/azure/information-protection/rms-client/use-client)

# [Develop & Customize apps](/azure/information-protection/develop/developers-guide)

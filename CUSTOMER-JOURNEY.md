# Customer journey and access

## 1. Tell KM what you need

Start with the existing website, its providers and the outcome you want:

- Edit or improve the current site.
- Build a new website.
- Add a customer or staff login.
- Build a management system.
- Connect an existing workflow or service.

KM identifies which access is needed for that work. A website does not need to move simply because KM will edit it.

## 2. Arrange the relevant access

| Connection | What it is for |
| --- | --- |
| Website builder or CMS | Editing and publishing the existing site through that platform. |
| GitHub | Access to the selected source repository and its change/build workflow. |
| Cloudflare or another host | Hosting applications and publishing deployments. |
| DNS provider | Domain records, website routing and agreed verification changes. |
| Google Search | Search Console, sitemaps and search reporting. |

The registrar, DNS provider, host and source repository may be different services. Connecting one does not provide access to the others.

### Quick connection

Where a supported app is available, the customer signs in with the provider, approves its permissions and selects the relevant resources. Organisation approval or additional provider setup may be required.

GitHub customers should select the website repositories needed for the work. Cloudflare customers approve the services required for their agreed website or application.

### Manual invitation

Customers can invite KM using their provider's collaborator or member process and complete the setup form while that is being arranged. An invitation marked as sent remains pending until KM accepts it and verifies the role.

Quick connection can be completed later on the same saved customer setup.

## 3. Check the editing and publishing path

KM confirms the correct website or repository, the access granted, and how changes reach production. Some sites need original source, build instructions or a provider editor as well as hosting access.

A source repository connection by itself does not prove that production publishing is configured.

## 4. Build and review

Work may involve a proposed source change, a draft pull request, a preview, or a separate application. A custom portal can sit beside the existing public website.

Authentication, roles, data storage and integrations are part of the application build. Adding a login button alone does not create those features.

## 5. Launch and hand over

Test the agreed workflow, check relevant permissions and publish the reviewed version. Provide access and recovery guidance appropriate to the project.

If a migration is required, preserve the existing DNS inventory and check email, certificates, external services and application data. Keep the old service available while the transition is validated.

Third-party services may have separate activation and billing. For example, approving R2 storage permissions does not activate an R2 subscription.

## Privacy

Use the provider's approval or invitation process. Do not put passwords, tokens, private keys or customer data in public GitHub issues. Use [KM's enquiry form](https://km-systems.co.nz/get-started/) for private project discussions.

# Roadmap and validation

This is the direction of the KM Systems website and customer-connection service. Planned work is not a promise of a delivery date or support for every provider.

## Foundation already in place

- Public KM website, examples and demonstrations.
- Customer setup form with saved progress and private KM review.
- Manual access guides for existing websites and hosting providers.
- Cloudflare app registration and customer connection flow.
- Tools for preparing and publishing Cloudflare changes, with deployment checks and rollback controls.
- GitHub app registration, selected-repository access and source-change proposals using branches and draft pull requests.
- Optional Google Search setup and reporting.

These features still require the customer's own approval and the relevant provider account, permissions and service activation.

## Validate complete customer journeys

- Complete customer-authorised pilots for both an existing website and a new application.
- Verify that source access, build tooling and production hosting work together.
- Exercise preview, publishing, failed deployments and recovery using real test projects.
- Check reconnect, revoked access and organisation approval.
- Confirm handover and the customer's ability to maintain their project.

Automated and local browser tests support this work. They do not replace a live customer-authorised pilot.

## Extend provider coverage

- Add provider discovery and clearer guidance for mixed registrar/DNS/hosting setups.
- Prepare Domain Connect templates and onboard them with supported DNS providers.
- Evaluate direct API or delegated-access integrations for other mainstream and New Zealand providers.
- Keep manual invitations available where automatic connection is unavailable or unsuitable.

An API or DNS template does not necessarily provide a visual website editor, a full DNS export, or a way to migrate an application.

## Make delivery repeatable

- Develop clean, repeatable website and portal starting points.
- Improve preview, review and handover.
- Provision isolated customer application resources with clear status and recovery steps.
- Build agreed authentication, roles and business workflows.
- Improve the record of what changed, what was approved and how it was deployed.

## Make migrations predictable

- Obtain and compare complete DNS records before changing nameservers.
- Preserve mail, verification, subdomains and other existing services.
- Separate DNS changes from website and application-data migration.
- Check certificates, redirects, integrations, users and subscriptions before retiring an old service.

## Keep expanding around real needs

Prioritise the workflows that customers actually use, then add integrations and automation where they reduce repeated work. Keep optional features and third-party costs clear rather than assuming every business needs the same setup.

# ShipSense Privacy Policy

**Last updated:** February 2026

ShipSense is a GitHub App designed to improve delivery clarity inside GitHub by adding structured, intent-aware delivery information to Issues and Pull Requests.

This policy explains what data ShipSense accesses, what it stores, and how that data is used.

---

## Information We Access

When installed, ShipSense may access the following GitHub data **only within the repositories where it is installed**:

- Pull Requests (metadata, state, base branch, body text)
- Issues (metadata, body text, labels)
- Issue and Pull Request comments
- Repository metadata
- GitHub Projects (only if explicitly enabled)

ShipSense does **not** access:

- source code contents
- user authentication data
- organization membership details
- private messages or discussions

---

## Information We Store

ShipSense stores **only the minimum data required** to operate reliably and avoid duplicate updates.

This includes:

- GitHub node IDs for Issues and Pull Requests
- IDs of ShipSense-generated comments (to update them safely)
- Repository-level configuration (e.g., production branch)
- Delivery intent metadata derived from labels
- Timestamps related to delivery status updates

ShipSense does **not** store:

- source code
- commit diffs
- user credentials
- personal data beyond what is already present in GitHub Issues or Pull Requests

---

## How We Use Information

The data ShipSense accesses and stores is used solely to:

- Link Pull Requests to Issues
- Display delivery intent (resolves, partial, reference)
- Update delivery status when Pull Requests change state
- Maintain a single, durable bot comment per Issue and Pull Request
- Prevent duplicate or spam comments

ShipSense does **not** use data for analytics, advertising, tracking, or resale.

---

## Data Retention

Stored data is retained only as long as necessary to maintain delivery state and comment continuity.

If ShipSense is uninstalled:

- No new data is collected
- Existing stored metadata is no longer updated
- Data may be deleted during routine cleanup

---

## Data Sharing

ShipSense does **not** share data with third parties.

All interactions occur exclusively between:

- GitHub
- the ShipSense service instance

---

## Security

ShipSense uses:

- GitHub webhook signature verification
- GitHub App authentication
- Minimal permission scopes
- Secure, encrypted connections to its database

No user credentials or tokens are stored.

---

## Changes to This Policy

This policy may be updated to reflect changes in functionality or operational requirements.

Significant changes will be reflected by updating the **Last updated** date.

---

## Contact

For questions, concerns, or data-related requests, contact:

**Email:** sohail.shiraj@hotmail.com

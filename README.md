# RoleReady

Import a resume, review career evidence, tailor a grounded draft, approve specific changes,
and export the saved result. Requires a RoleReady account and OAuth authorization.
Generation uses the account's existing allowance. RoleReady prepares resumes; it does not
submit applications or promise a hiring outcome.

- Website: https://roleready.designxdevelop.workers.dev/
- Remote MCP: https://roleready.designxdevelop.workers.dev/api/mcp
- Setup and help: https://roleready.designxdevelop.workers.dev/support
- Privacy: https://roleready.designxdevelop.workers.dev/privacy
- Terms: https://roleready.designxdevelop.workers.dev/terms
- Publisher: Design X Develop LLC — austin@designxdevelop.com

Connect the remote MCP server in your agent, sign in to RoleReady, and authorize the requested
scopes. The existing site-password gate still applies to browser sign-in and consent. Upload resume files directly to RoleReady through its authenticated browser fallback;
local paths cannot be read by the remote server. In Claude, do not extract attachments or
conversation history into tool arguments. Explicitly supplied resume text can be imported. Review selected facts and metadata before confirming.

This package contains one guided skill and a remote server connection. It contains no keys,
account credentials, local executable server or lifecycle hooks. Installing the package does
not authorize access to an account. Tool calls and exports remain account-scoped.

License: Proprietary. No open-source license is granted by this package. Use of the connected
RoleReady service is governed by the terms linked above.

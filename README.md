# Fjordova for Cursor

Connect Cursor to the business systems and data sources enabled for your Fjordova account. Ask questions about the data you can access and, where supported, prepare changes for review. Proposals follow your company's selected confirmation level before execution.

Publisher: Gobrand och Borggren AB (559605-3032). Support: support@fjordova.com.

## Availability

The shared Fjordova MCP endpoint is `https://mcp.fjordova.ai/mcp`.

Fortnox is the existing production integration. Spiris and additional sources, including Bolagsverket, must not be considered available through this connector until production activation and end-to-end access have been verified. Installation, OAuth sign-in and tool calls from Cursor through the shared endpoint are still awaiting verification.

The tools you can use depend on your connected systems, selected company, enabled modules, licences and permissions. A shared URL does not grant access to an unconnected system.

## Connect

[Add Fjordova to Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=Fjordova&config=eyJ1cmwiOiJodHRwczovL21jcC5mam9yZG92YS5haS9tY3AifQ%3D%3D)

The link adds the Fjordova MCP configuration. Complete OAuth sign-in and check the selected company and granted access. The package contains no API key or static client secret.

If you have an older system-specific connection, create a new OAuth connection for the shared endpoint. Changing a URL does not transfer the previous authorization. Check that the new connection works before removing the old one.

To evaluate the plugin locally, copy the repository to `~/.cursor/plugins/local/fjordova.ai`, reload Cursor and open Customize. Your organization's settings may restrict local plugins. See [Cursor's plugin instructions](https://cursor.com/docs/plugins#test-plugins-locally).

## Try it

- Which company and connected systems can I access?
- Summarize the information available for my selected company.
- If supported, prepare a proposed customer update and show the preview without executing it.

Review each proposal before confirmation. Depending on your company's settings, the AI app may confirm a change after your approval in the conversation, or you may need to confirm it on a Fjordova page. Do not assume that every change requires a separate webpage confirmation.

## Verification status

This package is a candidate for the shared endpoint. Historical tests using a system-specific endpoint do not verify this connection. The repository does not establish publication or approval in Cursor Marketplace. See [STATUS.md](STATUS.md) for the current validation record.

## Links

- [Website](https://fjordova.ai)
- [Connection guide and support](https://fjordova.ai/koppla)
- [Privacy policy](https://fjordova.ai/integritetspolicy)
- [Terms of service](https://fjordova.ai/villkor)
- [Data processing agreement](https://fjordova.ai/personuppgiftsbitradesavtal)

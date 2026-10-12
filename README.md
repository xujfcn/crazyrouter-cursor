# Cursor with Crazyrouter

Updated 2026-10-12. Configure a supported custom model through Cursor's API-key settings.

1. Create an API key at [Crazyrouter](https://crazyrouter.com/console/token).
2. Open Cursor Settings → Models / API Keys. Labels may differ by Cursor version.
3. Configure the OpenAI-compatible provider and override its base URL with `https://crazyrouter.com/v1`.
4. Enter your key locally and add a supported exact model ID, such as `gpt-4o-mini` or `claude-sonnet-4-6`.
5. Verify the key and send a small chat request before using it on a project.

Custom API keys apply only to features Cursor allows to use them. They do not replace a Cursor subscription or guarantee that Tab, Composer or every built-in feature uses this gateway. Check [Cursor's current API-key documentation](https://cursor.com/docs/settings/api-keys).

Do not add UTM parameters to the API URL or paste invented `openai.apiBaseUrl` settings into VS Code settings. Use the controls documented by the installed Cursor version.

## Models, prices and errors

Read [current models](https://crazyrouter.com/en/models) and [prices](https://crazyrouter.com/en/pricing). Input/output/cache costs and account limits vary. This guide does not estimate Cursor subscription savings or promise unlimited usage.

HTTP 400: check model capabilities and parameters. HTTP 401/403: check key and account permissions. HTTP 404: check model spelling and the request path. HTTP 429: check balance and rate limits.

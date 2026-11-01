# Privacy

Unless a product-specific note below says otherwise, this Action processes supported files locally inside the GitHub Actions workspace. It does not upload repository source, prompts, secret values or customer data to ECZ-ID and emits no hidden telemetry.

GitHub itself processes workflow logs and artifacts according to your GitHub plan and settings. Do not place sensitive values in public workflow inputs or logs.

Commercial/acquisition links carry only bounded public-safe source/surface/result tokens; repository names, customer identifiers, ECZ-IDs and technical finding payloads are excluded from the attribution contract.

## Website Security network request

This Action sends one value to ECZ-ID: the normalized **public website hostname** supplied in the `website` input. It does not send repository source, workflow source, paths, query strings, credentials or secret values. The public check is passive/non-intrusive and is not a penetration test.

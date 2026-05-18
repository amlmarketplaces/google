# amlmarketplaces/google

Claude Code marketplace federating all `@amlplugins/google-*` plugins.

## Install

Add to your project's `.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "aml-google": {
      "source": { "source": "github", "repo": "amlmarketplaces/google" }
    }
  },
  "enabledPlugins": {
      "google-admin@aml-google": true,
      "google-admob@aml-google": true,
      "google-ads@aml-google": true,
      "google-adsense@aml-google": true,
      "google-analytics@aml-google": true
    }
}
```

Then launch Claude Code in the project. The marketplace is fetched from `amlmarketplaces/google`, cached under `~/.claude/plugins/cache/aml-google/`, and each enabled plugin is loaded from its `amlplugins` source repo.

## Plugins (83 total)

- `google-admin` — [@amlplugins/google-admin](https://github.com/amlplugins/google-admin)
- `google-admob` — [@amlplugins/google-admob](https://github.com/amlplugins/google-admob)
- `google-ads` — [@amlplugins/google-ads](https://github.com/amlplugins/google-ads)
- `google-adsense` — [@amlplugins/google-adsense](https://github.com/amlplugins/google-adsense)
- `google-analytics` — [@amlplugins/google-analytics](https://github.com/amlplugins/google-analytics)
- `google-auth` — [@amlplugins/google-auth](https://github.com/amlplugins/google-auth)
- `google-books` — [@amlplugins/google-books](https://github.com/amlplugins/google-books)
- `google-business-profile` — [@amlplugins/google-business-profile](https://github.com/amlplugins/google-business-profile)
- `google-calendar` — [@amlplugins/google-calendar](https://github.com/amlplugins/google-calendar)
- `google-campaign-manager-360` — [@amlplugins/google-campaign-manager-360](https://github.com/amlplugins/google-campaign-manager-360)
- `google-chat` — [@amlplugins/google-chat](https://github.com/amlplugins/google-chat)
- `google-classroom` — [@amlplugins/google-classroom](https://github.com/amlplugins/google-classroom)
- `google-cloud-apigee` — [@amlplugins/google-cloud-apigee](https://github.com/amlplugins/google-cloud-apigee)
- `google-cloud-artifact-registry` — [@amlplugins/google-cloud-artifact-registry](https://github.com/amlplugins/google-cloud-artifact-registry)
- `google-cloud-asset` — [@amlplugins/google-cloud-asset](https://github.com/amlplugins/google-cloud-asset)
- `google-cloud-automl` — [@amlplugins/google-cloud-automl](https://github.com/amlplugins/google-cloud-automl)
- `google-cloud-bigquery` — [@amlplugins/google-cloud-bigquery](https://github.com/amlplugins/google-cloud-bigquery)
- `google-cloud-bigtable` — [@amlplugins/google-cloud-bigtable](https://github.com/amlplugins/google-cloud-bigtable)
- `google-cloud-build` — [@amlplugins/google-cloud-build](https://github.com/amlplugins/google-cloud-build)
- `google-cloud-composer` — [@amlplugins/google-cloud-composer](https://github.com/amlplugins/google-cloud-composer)
- `google-cloud-compute` — [@amlplugins/google-cloud-compute](https://github.com/amlplugins/google-cloud-compute)
- `google-cloud-container` — [@amlplugins/google-cloud-container](https://github.com/amlplugins/google-cloud-container)
- `google-cloud-dataflow` — [@amlplugins/google-cloud-dataflow](https://github.com/amlplugins/google-cloud-dataflow)
- `google-cloud-dataform` — [@amlplugins/google-cloud-dataform](https://github.com/amlplugins/google-cloud-dataform)
- `google-cloud-dataproc` — [@amlplugins/google-cloud-dataproc](https://github.com/amlplugins/google-cloud-dataproc)
- `google-cloud-datastore` — [@amlplugins/google-cloud-datastore](https://github.com/amlplugins/google-cloud-datastore)
- `google-cloud-deploy` — [@amlplugins/google-cloud-deploy](https://github.com/amlplugins/google-cloud-deploy)
- `google-cloud-dialogflow` — [@amlplugins/google-cloud-dialogflow](https://github.com/amlplugins/google-cloud-dialogflow)
- `google-cloud-dialogflow-cx` — [@amlplugins/google-cloud-dialogflow-cx](https://github.com/amlplugins/google-cloud-dialogflow-cx)
- `google-cloud-discovery-engine` — [@amlplugins/google-cloud-discovery-engine](https://github.com/amlplugins/google-cloud-discovery-engine)
- `google-cloud-dlp` — [@amlplugins/google-cloud-dlp](https://github.com/amlplugins/google-cloud-dlp)
- `google-cloud-dns` — [@amlplugins/google-cloud-dns](https://github.com/amlplugins/google-cloud-dns)
- `google-cloud-document-ai` — [@amlplugins/google-cloud-document-ai](https://github.com/amlplugins/google-cloud-document-ai)
- `google-cloud-error-reporting` — [@amlplugins/google-cloud-error-reporting](https://github.com/amlplugins/google-cloud-error-reporting)
- `google-cloud-firestore` — [@amlplugins/google-cloud-firestore](https://github.com/amlplugins/google-cloud-firestore)
- `google-cloud-functions` — [@amlplugins/google-cloud-functions](https://github.com/amlplugins/google-cloud-functions)
- `google-cloud-iam` — [@amlplugins/google-cloud-iam](https://github.com/amlplugins/google-cloud-iam)
- `google-cloud-kms` — [@amlplugins/google-cloud-kms](https://github.com/amlplugins/google-cloud-kms)
- `google-cloud-logging` — [@amlplugins/google-cloud-logging](https://github.com/amlplugins/google-cloud-logging)
- `google-cloud-memorystore-redis` — [@amlplugins/google-cloud-memorystore-redis](https://github.com/amlplugins/google-cloud-memorystore-redis)
- `google-cloud-monitoring` — [@amlplugins/google-cloud-monitoring](https://github.com/amlplugins/google-cloud-monitoring)
- `google-cloud-natural-language` — [@amlplugins/google-cloud-natural-language](https://github.com/amlplugins/google-cloud-natural-language)
- `google-cloud-pubsub` — [@amlplugins/google-cloud-pubsub](https://github.com/amlplugins/google-cloud-pubsub)
- `google-cloud-recaptcha-enterprise` — [@amlplugins/google-cloud-recaptcha-enterprise](https://github.com/amlplugins/google-cloud-recaptcha-enterprise)
- `google-cloud-resource-manager` — [@amlplugins/google-cloud-resource-manager](https://github.com/amlplugins/google-cloud-resource-manager)
- `google-cloud-retail` — [@amlplugins/google-cloud-retail](https://github.com/amlplugins/google-cloud-retail)
- `google-cloud-run` — [@amlplugins/google-cloud-run](https://github.com/amlplugins/google-cloud-run)
- `google-cloud-scheduler` — [@amlplugins/google-cloud-scheduler](https://github.com/amlplugins/google-cloud-scheduler)
- `google-cloud-secret-manager` — [@amlplugins/google-cloud-secret-manager](https://github.com/amlplugins/google-cloud-secret-manager)
- `google-cloud-spanner` — [@amlplugins/google-cloud-spanner](https://github.com/amlplugins/google-cloud-spanner)
- `google-cloud-speech` — [@amlplugins/google-cloud-speech](https://github.com/amlplugins/google-cloud-speech)
- `google-cloud-storage` — [@amlplugins/google-cloud-storage](https://github.com/amlplugins/google-cloud-storage)
- `google-cloud-tasks` — [@amlplugins/google-cloud-tasks](https://github.com/amlplugins/google-cloud-tasks)
- `google-cloud-text-to-speech` — [@amlplugins/google-cloud-text-to-speech](https://github.com/amlplugins/google-cloud-text-to-speech)
- `google-cloud-trace` — [@amlplugins/google-cloud-trace](https://github.com/amlplugins/google-cloud-trace)
- `google-cloud-translate` — [@amlplugins/google-cloud-translate](https://github.com/amlplugins/google-cloud-translate)
- `google-cloud-vertex-ai` — [@amlplugins/google-cloud-vertex-ai](https://github.com/amlplugins/google-cloud-vertex-ai)
- `google-cloud-video-intelligence` — [@amlplugins/google-cloud-video-intelligence](https://github.com/amlplugins/google-cloud-video-intelligence)
- `google-cloud-vision` — [@amlplugins/google-cloud-vision](https://github.com/amlplugins/google-cloud-vision)
- `google-custom-search` — [@amlplugins/google-custom-search](https://github.com/amlplugins/google-custom-search)
- `google-display-video-360` — [@amlplugins/google-display-video-360](https://github.com/amlplugins/google-display-video-360)
- `google-docs` — [@amlplugins/google-docs](https://github.com/amlplugins/google-docs)
- `google-drive` — [@amlplugins/google-drive](https://github.com/amlplugins/google-drive)
- `google-firebase` — [@amlplugins/google-firebase](https://github.com/amlplugins/google-firebase)
- `google-firebase-admin` — [@amlplugins/google-firebase-admin](https://github.com/amlplugins/google-firebase-admin)
- `google-fonts` — [@amlplugins/google-fonts](https://github.com/amlplugins/google-fonts)
- `google-forms` — [@amlplugins/google-forms](https://github.com/amlplugins/google-forms)
- `google-generative-ai` — [@amlplugins/google-generative-ai](https://github.com/amlplugins/google-generative-ai)
- `google-gmail` — [@amlplugins/google-gmail](https://github.com/amlplugins/google-gmail)
- `google-identity-toolkit` — [@amlplugins/google-identity-toolkit](https://github.com/amlplugins/google-identity-toolkit)
- `google-maps` — [@amlplugins/google-maps](https://github.com/amlplugins/google-maps)
- `google-meet` — [@amlplugins/google-meet](https://github.com/amlplugins/google-meet)
- `google-merchant` — [@amlplugins/google-merchant](https://github.com/amlplugins/google-merchant)
- `google-people` — [@amlplugins/google-people](https://github.com/amlplugins/google-people)
- `google-search-ads-360` — [@amlplugins/google-search-ads-360](https://github.com/amlplugins/google-search-ads-360)
- `google-search-console` — [@amlplugins/google-search-console](https://github.com/amlplugins/google-search-console)
- `google-sheets` — [@amlplugins/google-sheets](https://github.com/amlplugins/google-sheets)
- `google-slides` — [@amlplugins/google-slides](https://github.com/amlplugins/google-slides)
- `google-tag-manager` — [@amlplugins/google-tag-manager](https://github.com/amlplugins/google-tag-manager)
- `google-tasks` — [@amlplugins/google-tasks](https://github.com/amlplugins/google-tasks)
- `google-wallet` — [@amlplugins/google-wallet](https://github.com/amlplugins/google-wallet)
- `google-youtube` — [@amlplugins/google-youtube](https://github.com/amlplugins/google-youtube)
- `google-youtube-analytics` — [@amlplugins/google-youtube-analytics](https://github.com/amlplugins/google-youtube-analytics)

## Related

- npm packages: `@amlplugins/google-*` published to GitHub Packages (`https://npm.pkg.github.com`).
- Aggregating parent: [`amlmarketplaces/aml`](https://github.com/amlmarketplaces/aml) — federates every `@amlplugins/*` plugin under a single marketplace.
- AML topology: see `.claude/rules/definitions/ageni.md` § "GitHub Topology" — this repository is a Tier-4 HUB-INSTANCE under the `amlmarketplaces/` Tier-3 HUB-ORGANIZATION.

> Built by `.claude/skills/aml/metateam/marketplace/test/cross-org-amlmarketplaces-batch.mjs`.

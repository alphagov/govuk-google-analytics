# govuk-google-analytics

Google Tag Manager(GTM) is a tag management system that lets users configure and instantly deploy tags. Almost anyone - with the right access permissions - will be able (and encouraged) to make changes to the GTM configuration by creating new versions as befits the needs. Although GTM is fairly robust in preventing tag configuration errors, breaking changes may still occur. 


We want to ensure that changes made to the GTM configuration do not cause adverse effects, so we have decided to create and maintain a backup, in this repo, that is isolated from the GTM from which we can recover to a working state should the need arise.

## Documentation

Our current implementation is documented at https://alphagov.github.io/govuk-google-analytics.

To modify this documentation, see `docs/README.md`.

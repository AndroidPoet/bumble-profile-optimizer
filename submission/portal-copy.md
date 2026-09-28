# OpenAI plugin submission

Use this copy for the **Skills only** submission type in the OpenAI plugin submission portal.

## Info

- **Plugin name:** Bumble Profile Optimizer
- **Category:** Entertainment
- **Short description:** Research-backed profile feedback and rewriting.
- **Long description:** Build a more distinctive and honest Bumble profile through screenshot audits, photo selection and ordering, conversational discovery, bio and prompt writing, badge and filter review, implementation support, and first-message strategy for Bumble's 72-hour match window. The process adapts to a complete rebuild or a focused request and keeps recommendations grounded in the user's real life rather than generic templates.
- **Website:** https://github.com/AndroidPoet/bumble-profile-optimizer
- **Support:** https://github.com/AndroidPoet/bumble-profile-optimizer/issues
- **Privacy:** https://github.com/AndroidPoet/bumble-profile-optimizer/blob/main/PRIVACY.md
- **Terms:** https://github.com/AndroidPoet/bumble-profile-optimizer/blob/main/TERMS.md
- **Logo:** `assets/bumble-profile-logo.png`
- **Developer identity:** Select the verified individual or business identity that owns the listing. Make the public developer name and support details match that identity.
- **Affiliation disclosure:** Independent, unofficial project. Not affiliated with or endorsed by Bumble Inc.

## Starter prompts

1. Audit my current Bumble profile from these screenshots.
2. Help me choose and order my six profile photos.
3. Interview me and write a Bumble bio and prompts that sound like me.

## Release notes

Initial public submission of a skills-only Bumble profile plugin for ChatGPT and Codex. It provides an eight-phase profile workflow backed by 29 cited studies, platform data, signaling theory, and clearly labelled practical guidance, updated for Bumble's August 2026 messaging rules. It contains no MCP server, authentication, telemetry, or external data store.

## Data and permissions

The plugin contains one skill and its research references. It uses the host product's existing conversation, image, and file capabilities. It does not connect to Bumble, access a dating account, create an account, authenticate a user, collect analytics, or retain data independently.

Users may supply profile screenshots, photos, bio, prompts, badges, filter settings, and personal background. The skill asks users to crop or blur unnecessary identifiers and unrelated third-party faces. It evaluates profile communication and image quality without attractiveness scoring, identity recognition, or sensitive-trait inference.

## Availability

Choose only the countries and regions in which the verified publisher is prepared to provide the listing and support it.

## Test cases

Use the five positive and four negative cases in [`test-cases.md`](test-cases.md).

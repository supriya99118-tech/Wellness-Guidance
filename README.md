# Meri Awaaz, Meri Duniya — Prototype

A mobile-friendly, static web prototype for a parent-guided baby story and bonding experience (initial focus: 6–12 months).

## Included in this prototype

- Story cards with sample on-device speech narration
- Browser-only voice recording, preview, and delete controls
- Language selector UI (prototype only; content is not translated dynamically)
- Parent-led activity cards
- Feature roadmap for family voice, multilingual stories, lullabies, memory journal, and AI narration feasibility

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static file server.

## Deploy

The site is static and can be deployed to Vercel without a build command or environment variables. Connect this repository to a Vercel project and use the repository root as the output.

## Important prototype limitations

- No backend, account system, database, or cloud audio storage is implemented.
- Voice recordings stay in the current browser page session and are not uploaded.
- The language selector changes its selected state only; it does not translate all content.
- Sample speech uses the browser's speech synthesis engine, which varies by device and language.
- AI narration and voice cloning are not implemented. They require provider evaluation, separate explicit consent, secure server-side integration, and a deletion policy.
- Story concepts are placeholders and must be reviewed for age suitability, cultural accuracy, rights, and respectful representation before publication.
- This prototype is not a medical or developmental assessment tool.

## Next implementation steps

1. Create a dedicated repository named `meri-awaaz-meri-duniya` and transfer these files when repository creation is available, or rename this starter repository.
2. Add managed adult authentication, private storage, consent records, and server-side ownership checks.
3. Add a content CMS and reviewed Hindi/English story pack.
4. Evaluate a licensed TTS provider for language coverage, pronunciation quality, costs, and retention terms.
5. Conduct mobile, accessibility, privacy, and caregiver usability testing.

## Privacy principles

No child account is needed for the prototype. Do not upload real family or child recordings to this demo. Production voice features should require adult consent, support deletion, use private storage, and never expose provider API keys in client code.

# World Without Limits

An offline-first, installable Progressive Web App for a solo superhero tabletop RPG using an original D10 dice-pool system inspired by classic Storyteller games.

## Publish with GitHub Pages

1. Create a GitHub repository named `world-without-limits`.
2. Upload **all files and folders** from this project to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Open the published URL in Chrome on Android.
7. In Chrome, use **⋮ → Add to Home screen** or **Install app**.

Use HTTPS (GitHub Pages provides it) for service-worker/offline installation support.

## Included in this starter build

- Responsive, dark, lightweight UI designed for phones.
- PWA manifest, service worker and installable home-screen experience.
- Local campaign saves via browser local storage.
- Campaign JSON export/import.
- Character sheet, three attribute groups, skills, powers, merits/flaws, backgrounds.
- Inventory register with multiple storage locations and no arbitrary slot limit.
- Locations, vehicles/properties, relationships/sidekicks and journal.
- D10 pool roller, physical-dice result entry, difficulty and configurable ones rules.
- Basic procedural scene/event generator and action interpretation templates.
- Settings for campaign automation, lethality, XP, performance and AI mode selection.

## Important limitations

This is a functional **starter prototype**, not a finished AI-powered game. The local DM currently uses simple keyword-based action classification and procedural event prompts. It does not yet simulate a complete tactical combat system, full NPC character sheets, autonomous long-term NPC schedules, deep branching adventures, or online AI.

The AI mode selector is a preference/UI placeholder. Online AI is deliberately not wired to a provider. Do not put private API keys in a public static website. A real online AI integration should use a secured backend/proxy. A downloadable on-device language model would need a compatible runtime and model files and should be tested against the exact Galaxy A32 variant.

## Storage and backups

Campaign data is stored in the browser's local storage on the device. Clearing browser site data can erase the campaign. Use **Journal → Export Campaign JSON** regularly. Exported JSON can be imported on another device.

## License / content

This starter contains original generic superhero RPG mechanics and no licensed comic-book character database or artwork. Add only content you have rights to distribute. The D10 rules are inspired by a genre of dice-pool RPGs, not copied from a proprietary rulebook.

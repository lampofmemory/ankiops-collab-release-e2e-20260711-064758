# RC Collab 20260711 064758

Welcome to the collaborative Anki deck `RC Collab 20260711 064758`. This deck is managed through [AnkiOps](https://github.com/visserle/AnkiOps), a bidirectional bridge between Anki and the filesystem. AnkiOps allows you to manage your decks in user-friendly Markdown files and to collaborate with others through GitHub.

> [!NOTE]
> AnkiOps collaboration is experimental. Check the [AnkiOps documentation](https://github.com/visserle/AnkiOps#how-does-collaboration-work-experimental) before upgrading an existing collection or changing the repository layout.

## Subscribe to this deck

Follow the [AnkiOps installation and initialization guide](https://github.com/visserle/AnkiOps#how-to-get-started) first. Subscribing to this public repository does not require a GitHub account.


Run these commands from the AnkiOps collection root:

```bash
ankiops collab subscribe visserle/ankiops-collab-release-e2e-20260711-064758
ankiops fa # short for ankiops files-to-anki
```

`collab subscribe` clones this repository into `collab/visserle/ankiops-collab-release-e2e-20260711-064758/` as an independent Git repository. `ankiops fa` syncs its deck files, media, and note types to Anki. Your AnkiOps collection can hold private decks and other shared repositories alongside it. Open Anki to confirm that `RC Collab 20260711 064758` and its subdecks appear.

## Keep the deck current

Run these commands from the AnkiOps collection root:

```bash
ankiops collab status visserle/ankiops-collab-release-e2e-20260711-064758
ankiops collab update visserle/ankiops-collab-release-e2e-20260711-064758
ankiops fa
```

`collab status` reports available GitHub changes and local work. `collab update` brings this repository's GitHub changes into its local Markdown files and tells you when `ankiops fa` is needed.

If an update overlaps with a local edit, AnkiOps leaves the subscribed repository unchanged and reports the location of preserved base, local, and upstream copies. Resolve the marked Markdown file there, remove its conflict markers, and run the reported update command again.

## Contribute to this deck

Edit your subscribed notes with either workflow:

- Edit the Markdown files under `collab/visserle/ankiops-collab-release-e2e-20260711-064758/`.
- Edit cards in Anki, then run `ankiops af` to write those changes back to the deck files.

Review and submit your changes from the AnkiOps collection root:

```bash
ankiops collab status visserle/ankiops-collab-release-e2e-20260711-064758
ankiops collab submit visserle/ankiops-collab-release-e2e-20260711-064758 --title "Clarify the explanation of spaced repetition"
```

`collab submit` commits changes from this shared repository and opens a pull request. It excludes private decks and changes from other subscribed repositories. If your GitHub account lacks write access, AnkiOps creates or reuses a fork for the submission.

Use an issue for questions about the deck's scope or content. Use a pull request for a concrete card, media, or note-type change.

## Maintain this deck as a publisher

Review incoming changes through GitHub pull requests. After merging a pull request, update your local subscription before making more edits:

```bash
ankiops collab update visserle/ankiops-collab-release-e2e-20260711-064758
ankiops fa
```

Use the same `status` and `submit` workflow for maintainer-authored changes.

See the [AnkiOps README](https://github.com/visserle/AnkiOps) for the full command reference and synchronization details.

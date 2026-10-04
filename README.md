# Persona Workshop

Turn your AI into a persona workshop: it interviews you, drafts your
custom character, and guides you to install it. Happy with the result?
It will even help you list it on the [Skill Harbor](https://theskillharbor.com) catalog.

## Install

1. Copy the full text of `SKILL.md`.
2. Paste it into your AI's persona, personality, or custom instructions section.
3. Say: "Let's build my persona."

The workshop interviews you a few questions at a time (character, name,
voice, principles, quirks), drafts the persona as three files, shows you
the full text, runs a privacy check, then guides the installation into
your own setup.

Your Muse already has a personality, shaped by all your chats. Capture
it: describe how it talks and acts, or paste excerpts, and the workshop
will shape it into clean files, scrub the private details, and help you
share it.

## Inside

- `SKILL.md` — the workshop master prompt
- `templates/` — blank templates for the three persona files
  (`personality.md`, `system-prompt.md`, `examples.md`)
- `examples/minibot-butler/` — a finished example persona. Try it as is,
  or reshape it into your own.

## The catalog option

When your persona is done, the workshop offers to help you share it:
it prepares the listing with you (name, tagline, description, free or
paid) and points you to the Skill Harbor submission page.

## Privacy

The workshop refuses to ship private data: a mandatory check strips real
names, contact details, and private memories before anything is shared.

---

Free. No code, no dependencies. Works with any agent that accepts custom
instructions.

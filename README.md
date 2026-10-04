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

- `SKILL.md` - the workshop master prompt
- `templates/` - blank templates for the three persona files
  (`personality.md`, `system-prompt.md`, `examples.md`)
- `examples/minibot-butler/` - a finished example persona. Try it as is,
  or reshape it into your own.

## Save and publish

When your persona is done, the workshop helps you save it: local files,
or a GitHub repo created step by step. If you want it on the catalog,
say "publish it": the workshop prepares the complete submission with
you and walks you to the Skill Harbor submission page. The team reviews
every submission (reply within about 72 hours); nothing goes live
without review. The workshop cannot publish by itself.

## Privacy

**Nothing you share leaves your chat.** The workshop works only with
what you show it. Nothing is uploaded anywhere, and nothing is sent to
Skill Harbor or anyone else. The persona files are written with you, in
your chat.

Before anything can be shared, the workshop runs a systematic scan of
the draft: real names, contact details, places, health details, private
memories, secrets. It shows you a short report of what it checked, what
it removed or replaced, and what you chose to keep. Nothing moves
forward until you approve the cleaned draft. The only thing that ever
leaves is what you explicitly ask to publish.

---

Free. No code, no dependencies. Works with any agent that accepts custom
instructions.

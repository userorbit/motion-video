# <Product> video kit

The look, rules, assets and code for every <Product> film. Each film prompt points here and only adds its story.
Sources: <landing URL>, <design system path>, <rules files>, product owner notes. When this file and the repo's rules files disagree, the repo wins.

## The brief (from the interview)
- Decision provenance: <user choices, source-derived facts, delegated defaults; include paths/URLs>.
- Audience, problem and one promise: <who, pain, takeaway>.
- Production mode: <one-pass | collaborative>.
- Plays: <landing loop, muted | social, with sound | launch or demo video>. Format: <16:9>. Length: <s>.
- Audio: <track, license | silent>; <voiceover language, voice/tone, script source | none>; <captions and SFX>.
- Must show: <features, by their product names>.
- Ingredients chosen: <brand element: logo animation / mascot / wordmark / UI only> · <words: punchlines / captions / none> · <transitions: magic moves / camera / cuts> · <extras: cursors, partner logos, proof moments, texture>.
- Ending: <tagline, call to action, URL>.

## Hard rules
<!-- Every rule with its source. Capture what the product says; do not copy another product's rules. -->
- Casing: (source)
- Type: <type styles, where mono is allowed> (source)
- Corners: <radius token> (source)
- Surfaces: background `<token>`; other surfaces only where the product has them: <which> (source)
- Borders and shadows: <what the product does> (source)
- Copy: <dashes, reading level, banned words> (source)
- Claims: see "Claims".

## Frame (<width>x<height>, 60 fps, <dark|light>)
- Framing: <full bleed | the product's own framing> (source or default)
- Words: <punchline or caption style from the interview: font, weight, size, accent>.
- Scenes: UI text only unless captions were chosen; read content 100 px from the edges.

## Color
| Token | Value | Use |
|---|---|---|
| background | | |
| foreground | | |
| muted foreground | | |
| surface | | only where the product shows one |
| border | | only where the product uses one |
| accent | | |
| status tones | | pass / warn / fail, from the product |

Hex only for anything that animates.

## Type
- Fonts and where they load from (local files at render time):
- Sizes at the delivery size: words __ px, headline __ px, UI 24+ px at 1080p.

## Signature elements
| Element | Look | Source | In films |
|---|---|---|---|
| Buttons (and their loading state) | | | keeps its width while loading |
| Status markers or badges | | | |
| Loader or spinner | | | frame-driven, frames every __ ms |
| Brand and partner icons | | | inline with names |
| Texture or pattern (if any) | | | calm behind UI |

## Logo and brand element
- Logo: (SVG path or component). Animation used: (draws itself / reveal / none).
- Character choice: <existing mascot | explicitly requested new film character | none>.
- Identity and source: <name, asset/model/reference path or URL; user-defined or delegated concept>.
- Fixed appearance: <species/object, silhouette, proportions, face, colors/material, accessories, 2D/2.5D/3D treatment>.
- Personality and motion: <2–3 traits, role, signature gesture, allowed expressions/poses, prohibited behavior, speaking or silent>.
- Continuity: <relative scale beside UI, persistent identity traits, reusable asset and pose source>.
- Never: (anything off brand).

## Cursors (if chosen)
- User: the OS arrow. Product: <its own cursor, if it automates> (source).
- A click = a short squash, then the target reacts.

## Components
| Need | Component (path) | In films: import / twin / redraw, and why |
|---|---|---|
| | | |

## Motion
- Direction: <mood words, pace, UI-led or character-led>.
- References: <path/URL and the specific qualities to borrow>; avoid: <anti-references or unwanted treatments>.
- Springs and easing from the product: (values).
- Transitions chosen: (magic moves / camera / cuts), and their rules.

## Claims
- What the product does (films may show):
- What it never does (films must not show):
- Approved lines:
- Words to avoid:

## Workspace
- Folder, Remotion version, webpack override (Tailwind, aliases), fonts, scripts (beats, audio-edit, stills, render, verify, beat-sheet).

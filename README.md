# Rhythmos - Combat Overhaul for ESO

Rhythmos is a combat pacing overhaul for ESO that introduces synchronized combat timing systems inspired by classic MMORPG combat flow and animation-driven action combat.

The addon implements a lightweight clientside combat framework that coordinates:
- weapon attack timing windows
- global skill cooldown pacing
- dodge roll and weapon swap lock states
- input buffering behavior
- synchronized combat feedback systems

Rhythmos extends the natural timing cadence already present within ESO's weapon combat system and reinforces it through deliberate action commitment and synchronized combat recovery windows.

Instead of emphasizing high-frequency weaving between abilities, combat actions become rhythmically chained through timing-aware input windows that preserve responsiveness while increasing combat readability, animation clarity and weapon weight.

The result is a more grounded and deliberate combat flow that remains fully connected to ESO's original action combat foundation.

---

# Core Systems

## Global Skill Cooldown Framework
Introduces a synchronized radial cooldown system for active abilities to establish consistent combat pacing and timing readability.

## Animation-Based Weapon Commitment
Light and Heavy Attacks temporarily restrict skill activation based on weapon-specific animation timing windows.

## Dynamic Action Lock System
Dodge rolling and weapon swapping are temporarily restricted during committed combat actions in order to preserve combat flow and animation continuity.

## Buffered Input Window
Abilities become queueable shortly before combat recovery completes, maintaining responsiveness while preserving animation commitment.

## Adaptive Weapon Timing
Different weapon categories use independent timing profiles synchronized to their natural combo cadence.

## Combat Pulse Feedback
Optional action bar pulse feedback communicates combat recovery completion and buffered skill execution timing.

## Accessibility Pulse Mode
Alternative high-visibility pulse feedback mode with stronger visual readability.

## Advanced Timing Configuration
All combat timing values can be adjusted manually for experimentation and advanced customization.

---

# Technical Characteristics

- Fully clientside implementation
- No combat automation
- No server-side modification
- Lightweight runtime behavior
- Compatible with keyboard/mouse and gamepad UI
- Compatible with most UI addons
- Uses ESO action layer systems and action slot hooks
- Designed around ESO's native combat timing behavior


# Credits & Special Thanks

Rhythmos evolved out of discussions, experiments and iterations within the ESO Players community and later specifically the addon developer space.

Special thanks to:

- @STUDLETON for the original early prototype work and foundational experimentation that helped make the first combat timing systems possible
- The ESOUI community on Gitter for documentation, examples and technical discussions around action layers and UI systems
- Dolgubon for creative input, technical direction and ongoing support during development
- ImPDA for helpful technical insights and implementation discussions
- The ESO Reddit community for the discussions that unexpectedly sparked the creation of this project
- ZeniMax Online Studios for providing an MMO architecture flexible enough to allow projects like this to exist
- Everyone who contributed feedback, testing and gameplay impressions throughout development

And finally:
thank you to everyone giving Rhythmos a try.

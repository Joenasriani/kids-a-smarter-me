# A SMARTER ME!

Play: https://kids-crown-of-greatness.vercel.app/

A SMARTER ME! is a five-scenario prosocial, routine and safety choice game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each run randomly selects five scenarios from a built-in bank of 20. Every scenario presents two choices; their left/right positions are randomized before display.

**scenario → two choices → record preferred/non-preferred source label → repeat for five scenarios → show advice or perfect-run role label**

The source marks one response in each scenario as the preferred `A` choice. Selecting that response increments the run’s preferred-choice count. Selecting the other response stores its associated advice for the result screen.

If one or more non-preferred choices are selected, the result screen lists only the associated advice for those scenarios. If all five preferred choices are selected, the game displays one random positive role label from its built-in result list.

## Topics represented

The scenario bank includes helping others, sharing, tidying, honesty, calming down, brushing teeth, handwashing, road safety, seatbelts, stove safety, polite requests, taking turns, responding when someone falls, laundry, helping family members, saving water and sneeze hygiene.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Interpretation boundary

Despite the title **A SMARTER ME!**, the implementation does not measure intelligence. Its result labels are game feedback derived from five scenario choices, not validated measures of intelligence, personality, morality, social development or psychological traits.

The repository contains no study measuring knowledge retention, behavior change or transfer outside the game.

## Repository scope

- `index.html` — complete playable game
- `emojis.com belt.png` — seatbelt image used by one scenario

Both files are preserved as game assets. Documentation and discovery files must not alter the scenario bank, preferred-choice labels, random selection, result logic, advice text, controls, visuals, image asset or runtime behavior.

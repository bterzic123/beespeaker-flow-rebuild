# Growth Audit — BeeSpeaker

**Live:** https://bterzic123.github.io/beespeaker-flow-rebuild/
**Prototype only:** https://bterzic123.github.io/beespeaker-flow-rebuild/?view=proto

BeeSpeaker asks every new learner nine questions: their level, their learning goal, the topics that matter and when they want to study. Then come two sign-up screens and a paywall that reads “Overcome the speaking barrier!” for everyone. This audit rebuilds the screens between the quiz and the price in BeeSpeaker’s own design, at BeeSpeaker’s own prices, so each goal gets its own answer on the screen where people decide.

It has two views:

- **Overview**: what we found, the two Meta ads you run today, five ranked ideas and the potential outcome.
- **Prototype**: three clickable phones side by side. Two are installs from your Meta ads (travel phrases, and “stop thinking about grammar”), one is from the App Store. Use the step chips, the Light / Dark switch or the 30-second walkthrough, or tap inside any phone.

## The five ideas

| # | Idea | Today | In the rebuild | Expected effect |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Ask for the account after the trial starts | Register and Create account sit between the loader and the price | The paywall follows the loader; your Register screen follows the purchase | CR +8% · ARPU +17% |
| 2 | Name their goal in the paywall headline | “Overcome the speaking barrier!” for everyone | “Speak English on your trip, from the first day” for a traveller, and a chip with their topics | CR +15–20% |
| 3 | Ask for reminders and the microphone after the trial starts | Notification, microphone and speech prompts before the price | Notifications on your Congratulations screen, the microphone before lesson one | CR +10–15% |
| 4 | Make the loader read their answers back | “AI is analyzing your answers” with a percentage | Each line names their level, goal, topics and study time | CR +10–15% |
| 5 | Put your rating next to the trial button | No rating on the paywall | “4.8 from 3K ratings on the App Store” and a learner review under the plans | CR +10–15% |

Every question you ask today is kept. Your App Tracking Transparency prompt stays on the first screen. Closing the paywall goes straight into the app, never to a second paywall.

## Grounding

Prices and copy come from the BeeSpeaker iOS first launch (US storefront): 100 $ a year shown as 9 $/mo, 44 $ every 3 months, “You save 43%”, and $99.99 a year with a 1-week free trial on Apple’s purchase sheet. 4.8 from 3K ratings is the US App Store listing (11 November 2026). 7M+ downloads and 3,000+ lessons are from beespeaker.com. The review and “Trusted by 5M+” come from your own in-app screen. Photos come from your App Store screenshots. The ads are from the Meta Ad Library as tracked by AppMagic.

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps, not measured lift for BeeSpeaker.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)

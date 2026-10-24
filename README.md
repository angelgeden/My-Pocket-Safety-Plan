# My Pocket Safety Plan

**Know your signs. Know what helps. Reach support fast.**

My Pocket Safety Plan helps you build a personal safety plan in minutes, see your early warning signs, and reach support in one tap. Check in with your emotions, learn which coping skills help, and share how to support you. Private by design: no account, no tracking, answers stay on your own device. Free and works offline. Not an emergency service.

👉 **Open the app:** https://YOUR-USERNAME.github.io/my-pocket-safety-plan/

---

## What it does

- **Guided setup.** A five-minute walkthrough with tap-to-add examples covers three zones: 🟢 green (steady), 🟡 yellow (early warning signs) and 🔴 red (overwhelmed). For each zone you note what helps, what to avoid and who to contact.
- **Right now.** One tap to call or text a crisis line, call your local emergency number, or reach your own safety person. These buttons also work from the lock screen.
- **Check in.** Pick from the 10 DBT emotion families (fear, anger, sadness, shame, guilt, joy, love, disgust, envy, jealousy), plus "not sure." Mark where you feel it in your body, rate how strong it is, and note any urges. The app suggests which zone you're in and shows that part of your plan.
- **Learn as you go (optional).** Short notes on what each emotion is for and its usual urge, a "which came first?" prompt for primary vs. secondary emotions, and an optional check-the-facts step that suggests opposite action when an emotion doesn't fit. At very high intensity these step aside so the plan and support come first. An Emotion guide collects it all. Tips can be turned off in Settings.
- **Did it help?** Rate how you feel before and after a coping skill. The skills that help you most move to the top.
- **Breathe with me.** A guided breathing pacer (in 4, out 6, or box breathing).
- **Skills library.** 32 DBT skills across mindfulness, distress tolerance, emotion regulation and interpersonal effectiveness, each with short steps, a "Try it" button and one-tap "Add to my plan."
- **Skill suggestions.** After a check-in, the app suggests a few skills that fit the emotion and how strong it is. At high intensity it only suggests calming, grounding skills.
- **Share with my support person.** Builds a short "how to support me" message you can review and send.
- **Update log and printable plan.** Every change is dated. Print or save a PDF with signature and date lines.
- **One plan, or a few.** Many people use one plan. If different settings bring different signs or need different help, add a separate plan for work, family, social situations or anything you name, and switch in one tap. Crisis lines, check-ins and skill ratings are shared across plans.
- **Optional passcode** for privacy on a shared device.
- **Easy on the eyes.** A calm dark theme by default with a light option (Settings → Appearance). Large tap targets, high contrast and minimal motion, so it stays usable when emotions run high.

## Privacy

- No accounts, no analytics, no tracking, no ads.
- Answers are saved only in the browser on the person's own device. They are never sent to this website or anyone else, including whoever shared the app.
- **Back up** downloads a private file. **Restore** loads it on another device, with an option to merge so nothing is lost.
- The passcode is a privacy screen, not encryption.

## Install it like an app

- **iPhone / iPad:** open the link in Safari → Share → **Add to Home Screen**
- **Android:** browser menu ⋮ → **Install app** or **Add to Home screen**
- **Computer:** in Chrome or Edge, click the install icon in the address bar

Once installed it works offline. On iPhone and iPad, installing also protects saved answers from Safari's automatic clean-up of sites you haven't visited in a while.

## Crisis lines

Built in for the 🇺🇸 United States, 🇨🇦 Canada, 🇬🇧 United Kingdom, 🇮🇪 Ireland, 🇦🇺 Australia and 🇳🇿 New Zealand. Everywhere else, the app links to [findahelpline.com](https://findahelpline.com), and people can add local numbers in **Settings**.

## Important

My Pocket Safety Plan is a personal planning tool. It is **not** an emergency service, medical device or substitute for professional care. It works best alongside a clinician and the people you trust. **If you are in immediate danger, call your local emergency number.**

---

## For maintainers

| File | Purpose |
|---|---|
| `index.html` | The whole app (HTML, CSS and JavaScript in one file, no build step) |
| `manifest.webmanifest` | Lets phones and computers install it |
| `sw.js` | Offline support |
| `icons/` | App icons |
| `fonts/` | Playfair Display and Inter font files (see `ADD-FONTS-HERE.txt`) |
| `HOW-TO-PUBLISH.txt` | Step-by-step publishing guide |

**Publishing an update:** replace `index.html`, then change `VERSION` in `sw.js` (for example `pocket-v1` → `pocket-v2`) so installed copies pick up the new version. People's saved answers are not affected.

**Fonts.** Headlines use *Playfair Display* and body text uses *Inter*, both free under the SIL Open Font License from Google Fonts. They're self-hosted from the `fonts/` folder, so the app never contacts Google and the fonts work offline. See `fonts/ADD-FONTS-HERE.txt` for the two files to add. Without them, similar built-in fonts are used.

**Skill content** lives in the `SKILLS` list in `index.html`. Edit a skill's wording there, or copy an entry to add a new one.

**Crisis numbers** live in the `COUNTRIES` list in `index.html`. Check them periodically against each service's official site.

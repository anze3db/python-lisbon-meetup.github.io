# Templates

Every example below comes from event #15 (3 December 2026, Gapstars, one talk by Ilya Dorman, with drinks and snacks). Match their structure and tone and swap in the new facts. Parts in [brackets] are optional and depend on the event.

## Contents
1. Meetup "Details" (Markdown, bilingual)
2. LinkedIn version of the details (Unicode bold)
3. LinkedIn post + first comment
4. X / Twitter
5. Mastodon
6. Discord
7. Email to the old meetup group (plain text)
8. Optional paragraphs (joint event, image consent, end time)

---

## 1. Meetup "Details"

Meetup supports Markdown. Make one agenda bullet per talk. If a speaker link was provided, use `[Name](url)`. Otherwise use `**Name**`.

```markdown
This month we're back at **Gapstars, Edifício Atrium Saldanha, 11th floor**, who are kindly hosting us again, with drinks and snacks! 🍻

Agenda:

- **18:30** Doors open, drinks & snacks
- Welcome and a short intro of Python Lisbon
- Talk by **Ilya Dorman**: "How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"
- One or more lightning talks ⚡
- Networking and socializing!

🇵🇹
Este mês voltamos ao **Gapstars, Edifício Atrium Saldanha, 11º andar**, que nos recebe mais uma vez, com bebidas e petiscos! 🍻

Agenda:

- **18:30** Abertura de portas, bebidas e petiscos
- Boas-vindas e breve apresentação do Python Lisbon
- Palestra de **Ilya Dorman**: "How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"
- Uma ou mais lightning talks ⚡
- Networking e convívio!
```

Without food, the opening line ends "…who are kindly hosting us again! 🐍" and the first agenda item is "Doors open, meet and greet" / "Abertura de portas e boas-vindas".

Event title convention: `#15 Python Lisbon Meetup at Gapstars`.

## 2. LinkedIn version of the details

Use the same text as section 1, but run every **bold** part through `scripts/unicode_bold.py`, replace "- " bullets with "• ", and remove all Markdown. A speaker link can't be clickable here, so use the bold name only.

```
This month we're back at 𝗚𝗮𝗽𝘀𝘁𝗮𝗿𝘀, 𝗘𝗱𝗶𝗳í𝗰𝗶𝗼 𝗔𝘁𝗿𝗶𝘂𝗺 𝗦𝗮𝗹𝗱𝗮𝗻𝗵𝗮, 𝟭𝟭𝘁𝗵 𝗳𝗹𝗼𝗼𝗿, who are kindly hosting us again, with drinks and snacks! 🍻

𝗔𝗴𝗲𝗻𝗱𝗮:

• 𝟭𝟴:𝟯𝟬 Doors open, drinks & snacks
• Welcome and a short intro of Python Lisbon
• Talk by 𝗜𝗹𝘆𝗮 𝗗𝗼𝗿𝗺𝗮𝗻: "How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"
• One or more lightning talks ⚡
• Networking and socializing!

🇵🇹
(the same conversion for the Portuguese half)
```

## 3. LinkedIn post + first comment

Start with a hook question taken from the talk topic. Leave the link out of the post.

```
Can you trust code your AI wrote without reading every line? 🤖

That's the question at our next 𝗣𝘆𝘁𝗵𝗼𝗻 𝗟𝗶𝘀𝗯𝗼𝗻 𝗠𝗲𝗲𝘁𝘂𝗽!

𝗜𝗹𝘆𝗮 𝗗𝗼𝗿𝗺𝗮𝗻 will give the talk "How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"

📅 Thursday, 3 December, 18:30
📍 Gapstars, Edifício Atrium Saldanha, 11th floor
🍻 Drinks and snacks, thanks to Gapstars

After the talk there will be lightning talks ⚡ and plenty of time to meet other Pythonistas in Lisbon. Got something you can show in 5 minutes? Bring it!

Free to attend. RSVP link in the comments 👇

#Python #Lisbon #AI #SoftwareEngineering #Meetup
```

First comment:
```
RSVP here 👉 https://www.meetup.com/python-lisbon-meetup/events/317505097/
```

## 4. X / Twitter (≤ 280; URLs count as 23 and emoji as 2)

```
Can you trust code your AI wrote without reading every line? 🤖

Ilya Dorman answers that at the next Python Lisbon Meetup, plus lightning talks ⚡

📅 Thu 3 Dec, 18:30
📍 Gapstars, Atrium Saldanha
🍻 Drinks & snacks

RSVP: https://www.meetup.com/python-lisbon-meetup/events/317505097/

#Python #Lisbon
```

## 5. Mastodon (≤ 500; URLs count as 23)

Use CamelCase hashtags so screen readers read them correctly. Suggest alt text for the image, e.g. "Python Lisbon Meetup #15 event card: 3 December 2026, 18:30, at Gapstars, with the talk title by Ilya Dorman".

```
Can you trust code your AI wrote without reading every line? 🤖

Our next Python Lisbon Meetup has a talk by Ilya Dorman: "How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"

📅 Thursday, 3 December, 18:30
📍 Gapstars, Edifício Atrium Saldanha, 11th floor
🍻 Drinks and snacks, thanks to Gapstars

Plus lightning talks ⚡ and time to meet other Pythonistas. Free to attend!

RSVP: https://www.meetup.com/python-lisbon-meetup/events/317505097/

#Python #Lisbon #PythonLisbon #AI
```

## 6. Discord

```
## 🐍 Python Lisbon Meetup #15: 3 December at Gapstars

Can you trust code your AI wrote without reading every line? 🤖

**Ilya Dorman** will give the talk **"How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line"**

📅 **Thursday, 3 December, 18:30**
📍 **Gapstars, Edifício Atrium Saldanha, 11th floor**
🍻 Drinks and snacks, thanks to Gapstars

**Agenda**
- 18:30 Doors open, drinks & snacks
- Welcome and a short intro of Python Lisbon
- Talk by Ilya Dorman
- One or more lightning talks ⚡
- Networking and socializing!

Got something you can show in 5 minutes? Bring a lightning talk! ⚡

👉 **[RSVP on Meetup](https://www.meetup.com/python-lisbon-meetup/events/317505097/)**

See you there! 👋
```

## 7. Email to the old meetup group (plain text)

The old group's members get a short, friendly email in plain text. Use English only, with no Markdown, no Unicode bold and a bare URL. Emoji start the date, place, talks and RSVP lines. Suggested subject: "Python Lisbon Meetup #15: 3 December at Gapstars".

```
Olá everyone! 👋

The Python Lisbon Meetup is back at Gapstars, and we'd love to see you there!

📅 December 3, 18:30
📍 Gapstars, Edifício Atrium Saldanha (11th floor), Lisbon

🎤 Talk:
Ilya Dorman — How I Learned to Stop Worrying and Love the Robot: How to tell if your AI builds slop without reading every line

Plus one or more lightning talks ⚡ There will also be drinks, snacks, and time to hang out and chat after the talks.

👉 RSVP here:
https://www.meetup.com/python-lisbon-meetup/events/317505097/

See you there!
```

How #14 differed (a joint event with two talks, food, and filming):
- Opening line: "Python Lisbon Meetup and PyData Lisbon are co-hosting a meetup, and we'd love to see you there!"
- Place with the neighbourhood: "📍 VW Innovation & Engineering Hub, Rato, Lisbon"
- "🎤 Two talks lined up:", then one "Speaker — Title" line per talk
- "There will also be food, drinks, and time to hang out and chat after the talks."
- The English image-consent paragraph from section 8 (with the 📸 but without the bold), between the talks and the RSVP link

Rules: date as "Month D, HH:MM" with no weekday. Never use relative time ("this month", "next week", "tomorrow"); the email often goes out in a different month from the event, so the date line says when. Talks as "Speaker — Title" with an em dash, and the title in the same case as on the Meetup page. Mention food or drinks only if the host has confirmed them, and lightning talks only if the event has them.

## 8. Optional paragraphs

**Joint event** (from #14):
> This time we're joining forces with [PyData Lisbon](https://www.meetup.com/pydata-lisbon/) at the **VW Innovation & Engineering Hub**, who are kindly hosting us, with food and drinks! 🍕
> PT: Desta vez juntamo-nos ao [PyData Lisbon](https://www.meetup.com/pydata-lisbon/) no **VW Innovation & Engineering Hub**, que nos recebe com comida e bebidas! 🍕

In a joint event, the welcome item becomes "Welcome from <host> and a short intro of Python Lisbon and <partner>".

**End time** (only when there is a hard one):
> The building closes at **20:30**, so we'll wrap up a little before then.
> PT: O edifício fecha às **20:30**, por isso vamos terminar um pouco antes.

**Image consent** (only when the event is filmed or photographed with consent forms):
> 📸 **Image consent: the event will be filmed and photographed.** At the entrance, every attendee will receive a paper form to fill in and sign, stating for each social media channel whether they allow their image to be shared.
> PT: 📸 **Consentimento de imagem: o evento vai ser filmado e fotografado**. À entrada, todos os participantes vão receber um formulário em papel para preencher e assinar, onde indicam, para cada rede social, se autorizam ou não a partilha da sua imagem.

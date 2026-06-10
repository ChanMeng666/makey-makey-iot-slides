# Speaker Notes — Touch the World, Talk to Code

A 20-minute teaching demo for students aged 12-18. Plain language, no jargon. The same notes
appear inside the deck: press **N** during the talk to show or hide them.

**Total budget: 20 minutes.** Times are cumulative.

---

## 1. Title (0:00 - 0:45)

Welcome. In 20 minutes we will build a real little gadget together. By the end you will have made a
toy you can play with your keyboard now, and with a banana in a few minutes. No coding experience
needed.

- Energy up. Promise a working toy by the end.

## 2. What is the Internet of Things? (0:45 - 3:00)

The Internet of Things is everyday things connected to computers. Point at the four cards (phone,
smartwatch, smart lights, game controller). Then walk the bottom strip left to right:

> something happens in the real world -> it becomes a signal -> the computer reads it -> the computer
> does something back.

That loop is the whole idea. We are about to build the simplest possible version of it.

- Keep it concrete. Do not define "sensor" or "protocol". Use things they already own.

## 3. Meet Makey Makey - and its secret (3:00 - 6:00)

This is the heart of the talk. Hold up the board if you have one. Makey Makey does one clever trick:
to the computer it looks exactly like a keyboard. Touching a banana is the same as pressing the Space
bar. Show the key map.

Because of that secret, we do not need the hardware to start. We can build our toy now and test it
with the keyboard, and later the very same toy works when you clip on a banana. Nothing in the code
has to change.

- This "it is just a keyboard" idea is the one thing they must remember.

## 4. Let's build it - just by asking (6:00 - 8:00)

You are not expected to write code. You describe what you want and the AI writes it.

- Route A (browser): safest in a classroom, nothing to install.
- Route B (Cursor): free for students, for building at home on your own computer.

Ask everyone to open one now so they are ready to type with you on the next slide.

## 5. Type this with me (8:00 - 10:30)

Read the prompt out loud slowly while everyone types it. Keep it exactly this short - it is enough.
Stress the last sentence, "make it work with a normal keyboard", because that is what lets them play
it without the board.

Once they press enter, give it a moment to generate. If a few students fall behind, that is fine -
the backup demo on the next slide works for everyone.

## 6. Play it (10:30 - 14:30)

Let them play their own version first. Then switch to the working demo (the orange button) as the
reliable shared example - it always works. Press a few keys so everyone hears the notes and sees the
keys flash.

Point out twice: nothing is plugged in, this is only the keyboard. Show that each on-screen key has a
Makey Makey label. Let the room get noisy and have fun.

## 7. Now add a banana (14:30 - 17:30)

Connect back to the loop from slide 2: real world, signal, computer, action. The big reveal: adding
the hardware changes nothing in the code - the banana just presses Space for you.

Plant one or two upgrade ideas for the hands-on time: record your own sounds, or add a score.

## 8. Your turn + thank you (17:30 - 20:00)

Recap the three steps so anyone can repeat this at home. Read the safety line clearly before handing
out the boards: food and foil only, hold the Earth bar to complete the circuit, never anything on
mains power. Thank them and hand over to the hands-on session. Leave the demo and handout links up.

---

### Backup plan

- If the AI tool is slow or blocked on the school network, present `demo/index.html` as the working
  toy and have students explore that. The teaching points are identical.
- The demo needs no internet except for fonts; it still works offline with fallback fonts.
- The deck needs internet only for Google Fonts; it degrades to Impact / system fonts offline.

# Speaker Notes — Touch the World, Talk to Code

A 20-minute teaching demo for students aged 12-18. Plain language, no jargon. We ask **Claude** to
build three little toys live. The same notes appear inside the deck: press **N** during the talk to
show or hide them.

**Total budget: 20 minutes.** Times are cumulative.

---

## 1. Title (0:00 - 0:45)

Welcome to the AI and Electronics Workshop. In 20 minutes we will build three little gadgets together,
mixing electronics and AI. We will ask an AI called Claude to write them for us. By the end you will
have toys you can play with your keyboard now, and with a banana in a few minutes. No coding experience
needed.

- Energy up. Promise three working toys by the end.

## 2. What is the Internet of Things? (0:45 - 2:30)

The Internet of Things is everyday things connected to computers. Point at the four cards (phone,
smartwatch, smart lights, game controller). Then walk the bottom strip left to right:

> something happens in the real world -> it becomes a signal -> the computer reads it -> the computer
> does something back.

That loop is the whole idea. We are about to build the simplest possible version of it, three times.

- Keep it concrete. Do not define "sensor" or "protocol". Use things they already own.

## 3. Meet Makey Makey - and its secret (2:30 - 4:30)

The heart of the talk. Hold up the board if you have one. Makey Makey does one clever trick: to the
computer it looks exactly like a keyboard. Touching a banana is the same as pressing the Space bar.
Show the key map.

Because of that secret, we do not need the hardware to start. We build our toys now and test them with
the keyboard, and later the very same toys work when you clip on a banana. Nothing in the code changes.

- This "it is just a keyboard" idea is the one thing they must remember.

## 4. Meet Claude, our AI builder (4:30 - 6:00)

You are not expected to write code. You describe what you want in plain English and Claude writes it.

- Open **claude.ai** in the browser and sign in - the free plan is enough, nothing to install.
- The key thing to show: when Claude writes a web app, it renders live in the **Artifact** preview
  panel right next to the chat. You see and play your toy immediately.

Get everyone to claude.ai now. We are about to build three toys in a row, typing the prompt together
each time.

## 5. Build 1 of 3 - Banana Piano (6:00 - 9:30)

Read the prompt out loud slowly while everyone types it into Claude. Keep it exactly this short. Stress
the last sentence, "make it work with a normal keyboard", because that is what lets them play it
without the board. Press enter and watch the Artifact panel build the piano live. Play a few keys.

This first build is the longest because you are also teaching the rhythm: ask, watch, play. If anyone
falls behind or the network is slow, open the finished piano with the orange button - it always works.

## 6. Build 2 of 3 - Beat Maker (9:30 - 12:30)

Faster now that they have the rhythm. Point out that we barely changed the prompt - we swapped musical
notes for drum sounds. Name that as a best practice: start from something that works and ask for one
small change. Build it live, then let two students tap a beat together. Backup is the orange button.

## 7. Build 3 of 3 - Catch Game (12:30 - 15:30)

The third toy shows the same trick builds a game, not just sound. Only the arrow keys are used, which
is perfect for a banana joystick later. Build it live and play one quick round so they see the score
climb. By now they should believe they can ask Claude for almost anything. If short on time, keep this
one briefest. Backup is the orange button.

## 8. Now add a banana (15:30 - 17:30)

Connect back to the loop from slide 2: real world, signal, computer, action. The big reveal: adding
the hardware changes nothing in the code - the banana just presses Space or an arrow for you.

Plant ideas for the hands-on time: turn the game into a banana joystick, make foil drum pads, or ask
Claude to change the sounds. Encourage them to keep asking Claude for small changes.

## 9. Your turn + thank you (17:30 - 20:00)

Recap the three steps so anyone can repeat this at home with Claude. Point them to the handout, which
has all three prompts. Read the safety line clearly before handing out the boards: food and foil only,
hold the Earth bar to complete the circuit, never anything on mains power. Thank them and hand over to
the hands-on session. Leave the demos and handout links up.

---

### Backup plan

- If Claude is slow or blocked on the school network, open the finished toys (`demo/piano/`,
  `demo/drums/`, `demo/catch/`, or the gallery at `demo/`) and have students play those. The teaching
  points are identical.
- The demos need no internet except for fonts; they still work offline with fallback fonts.
- The deck needs internet only for Google Fonts; it degrades to Impact / system fonts offline.

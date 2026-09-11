# Le Stick - Controller Stick Training App

Browser-based stick training app.

Open [le-stick.html](https://html-preview.github.io/?url=https://github.com/SephSwain/le-stick/blob/main/le-stick.html) to play.

## Training and series

Choose an individual exercise on the right or a series on the left with the controller's directional pad (or click its button), then press **A** to start. The total timer is on the left, above the series. **B** stops the current exercise and the entire series.

**10 ?** asks for ten single movements in randomly chosen directions. The arrow and highlighted corridor show the current direction. Reach its target and return to the center to receive the next direction; consecutive directions may match. A mistake resets the timer and repetitions while keeping the current direction for the retry. This exercise is available individually and in **endless random**, but is excluded from **Skill Check**.

- **endless random** is the animated neon infinity button on the left. Its Liquid Chaos artwork uses a vivid arcade palette, flowing loops and moving pixels, all embedded in the HTML. It keeps choosing a random exercise after each successful completion until you stop it.
- **Skill Check** (previously **all**) is a fixed benchmark of your current stick control. It always plays these eight exercises in their original order: ↑, ↓, ←, →, ↑↓, ↓↑, ←→, →←. New exercises and the list's error ranking do not change this test. The series ends after the eighth exercise. Its arcade button shows an animated performance gauge and your best completed total time. The needle and neon bars are decorative; your actual result is the total time. Existing records from **all** are retained.
- **Total** matches the exercise timer in individual training. During a series it measures the full elapsed time since the series started, including time spent on failed attempts.

A mistake resets the current exercise's timer and repetition count. The series total keeps running through mistakes and automatic exercise changes. Improving an exercise best or the total best for **Skill Check** plays the best-time sound.

Each completed repetition plays a short tone after returning to the center. The tone rises with progress through the exercise, covering one octave with a slightly lower base pitch, and starts low again after a mistake or a new exercise. The final repetition plays a distinct multi-note completion fanfare instead. An improved best time retains its own record sound.

The red **X** counter beside the exercise timer counts errors throughout the current run, including failed attempts. Completing an exercise saves its lowest error count independently of its best time, in individual training and both series modes. Aborted runs do not update records.

Each exercise button shows this best error count in red, right-aligned after its name (**123 X**). Exercises are sorted by highest best error count first; exercises without an error record appear first as **— X**. A new run starts its error counter at zero.

Errors clear the trail, mark the error position with a thick red X, and play a longer error tone. The X stays at that position until a successful target clears it or a new error replaces it. Trail drawing resumes after returning to the center.


## Code Quality

This is 100% unreviewed code from Codex.
Use at your own risk.

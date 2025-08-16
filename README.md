#### lyrics-annotator
##### Annotate lyrics for singing. Done by GPT-5.
---

Write me a simple app in HTML/CSS/JS. This is a lyrics annotator that takes in lyrics and outputs them with the following logic: 1. Pinyin Conversion (Initial Step): For every Chinese character, convert it to its full pinyin. 2. Look at the first letter of the pinyin you found in Step 1. If this first letter is one of "d, t, n, l, g, k": Take that single initial letter (e.g., 'l' from 'lan'). Move it to the front of the Chinese character. Then, write the rest of the pinyin after the Chinese character. Crucially: The initial letter is moved, not duplicated. So, 'lan' becomes 'l藍an', not 'l藍lan'. If the first letter of the pinyin is not one of "d, t, n, l, g, k", then this rule does not apply, and the character-pinyin pairing remains as it was. 3. Final Adjustment for "n" or "ng" Endings: After applying Rule 2 (if applicable), look at the pinyin part of the annotated character. If this pinyin ends in "n" or "ng": Remove all English letters that appear before the final "n" or "ng" in that pinyin. Only the "n" or "ng" should remain after the Chinese character (and any prepended initial from Rule 2). 4. Pinyin Removal for Unedited Characters: For any characters that did not undergo any modification from either Rule 2 or Rule 3, simply remove their pinyin entirely. Only the Chinese character should remain.

---

rewrite this app from scratch and make it beautiful

---

Think harder -- the color scheme of the app should be light mode

---

Can you create a brand new repository on my Github and push this code to github pages?

_No, no it cannot_. I did that :) 

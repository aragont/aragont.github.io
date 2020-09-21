## Quest for two phones

This is a quest assignment.

The initial QR code is printed on paper. The player reads it to his smartphone and goes to the page with the new QR code. The page address looks like http://example.com?answer=12  and the goal is to find the correct answer.

The player can either enter numbers in the URL manualy or try to scan a new code. After three or four consecutive scans, the correct answer will be displayed. The difficulty of the task is that the player cannot scan the screen of his own smartphone.

The advantage will be given to a team of two players who will scan each other's smartphone screens.

A good starting point might be a QR code pointing to a page with an answer equal to zero.

![initial answer equal to zero](https://aragont.github.io/quest42phones/answer_eq_0.png)

This project use [qrcode.js](https://davidshimjs.github.io/qrcodejs/) library.

# HallTicket Downloader 9000 🎟️

Welcome to the HallTicket Downloader 9000! This project was born out of a classic case of "necessity is the mother of invention" during my 2nd year of engineering in computer science. Picture this: it's April 22, 2022, and we're all geared up for our first offline exam after what felt like a century of virtual exams thanks to our dear friend, COVID-19. But alas! The universe had other plans for us.

## The Bug that Started it All 🐞
On April 21, 2022, the eve of our big offline exam, we received the golden ticket - our hall tickets - on the student portal. Excitement was in the air, until we encountered a pesky bug that prevented us from downloading our hall tickets. Panic ensued, but in the face of adversity, some brilliant minds in my class concocted a solution: "Hey, what if we tweak some CSS properties and take a screenshot of the entire page?" Ingenious, right? Well, almost.

## The Glitch in the Matrix 🕶️
Turns out, our CSS wizardry wasn't foolproof. It worked on some screens, but not all. Cue disappointment and a collective sigh of "back to the drawing board." But fear not, for in the depths of adversity, inspiration struck!

## The Birth of a Legend 💡
Armed with two screens (one dedicated solely to logging intercepted traffic in Burp Suite - because why not?), I embarked on a journey to crack the code and retrieve our elusive hall tickets. Lo and behold, amidst the sea of GET requests, I stumbled upon a gem - a GET request containing the sacred parameter known as "PRN" (Personal Roll Number). A light bulb went off in my head - what if we could manipulate this PRN parameter to access anyone's hall ticket?

## From Zero to Hero 🚀
With newfound determination and a sprinkle of JavaScript magic, I whipped up a humble index.html page where users could input their PRN and voila! The HallTicket Downloader 9000 was born. I deployed it on GitHub faster than you can say "exam cram," and within minutes, I became the talk of the town - or should I say, the campus.

## How to Use
1. Input your PRN (Personal Roll Number).
2. Click the magical button.
3. Behold! Your hall ticket appears like a majestic phoenix rising from the ashes.

## Credits
This project wouldn't have been possible without the unwavering support of two trusty screens. Here's to thinking outside the box and embracing the chaos!


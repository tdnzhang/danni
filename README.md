Danni
丹妮
https://danni--tdnzhang.replit.app


I'm a heritage Mandarin learner, which means I grew up hearing Chinese at home but was never formally taught it growing up in the US. I can hold a conversation and my tones are decent, but I have a lot of gaps especially in written vocab, formal contexts, and anything outside of what you'd talk about with family. The issue isn't that I'm a beginner, it's that my vocabulary is really uneven depending on the situation.
Every tool I found was built for people starting from zero, which wasn't really my problem. Duolingo wants to teach me "the apple is red" when I needed words like 游刃有餘, 破罐子破摔, and enough vocabulary to get through a conversation without switching to English mid-sentence. So I built a tool that would help me personally learn in a way I found efficient and straightforward.

What's in it
The vocab comes from 5 years of my actual Chinese class notes and homework assignments going back to 2020, songs I listen to tagged by song so I remember the context, idioms with full etymological breakdowns, business and MBA vocabulary, grammar patterns, and modern slang and Taiwanese internet terms. Not a generic HSK list, just words I've actually encountered in real situations.
Currently at 266 words and growing. Having varied sources makes it more useful as a learning tool since you end up seeing the same word across different contexts, which helps it actually stick.

How it works
Built on SM-2 spaced repetition, the same algorithm behind Anki. The idea is you review words at increasing intervals timed to right before you'd forget them. After each card you rate yourself (again / hard / good / easy) and the app schedules the next review based on that. Words you struggle with come back sooner, words you know well get pushed out further.
Each word has pinyin, bopomofo, etymology explaining why the word means what it means rather than just a made up mnemonic, component breakdowns with pronunciation hints, example sentences, connotation and register tags so I know if something is casual or formal, audio via browser TTS, and a source tag so I remember where I first saw it.
The app pulls live from Google Sheets so I can add new words from class or a new song without touching any code. SM-2 progress saves in localStorage so it remembers where I left off between sessions.

Stack
Single HTML file. Google Sheets as the live word bank, SM-2 progress in localStorage, Web Speech API for audio, hosted on Replit. Built with Claude for code generation and vocab enrichment.

What I'd add next
An AI enrichment page where I can paste song lyrics or class notes and it auto-generates full cards via Claude API. Better interval display so I can see exactly when each word is due. And honestly at some point I'd want to open this up for other heritage learners since there really isn't a good tool out there for this specific use case. The vocab a heritage speaker needs is really domain specific and doesn't map neatly onto any existing curriculum.

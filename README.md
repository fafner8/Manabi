[Download the deck here](https://github.com/fafner8/Manabi/releases)

Note: the deck is not affiliated with any other project or resource called Manabi.

# Manabi 2.7k highlights

Manabi is a new Japanese N+1 core Anki deck, which aims to expand and improve upon other existing core decks for beginner learners of Japanese. Manabi is not a simple repackage of the old core 2k/6k decks but rather it makes use of a much wider variety of example sentences, all with audio and furigana, newly re-ordered, that use natural and colloquial language, not available in other core decks. 

<b> Introduces vocabulary following N+1 </b> – All example sentences introduce only one new word per card, with very few exceptions.*

<b> Gradually introduces kanji, one at a time </b> – Starts with simple kanji and gradually introduces words with more complicated kanji, following N+1 for new kanjis (as much as possible).

<b> Rich selection of vocabulary </b> – words drawn from multiple types of content: Netflix subtitles, easy Japanese YouTube channels, slice-of-life anime, and more, covering both colloquial spoken language and more formal and advanced kinds of vocabulary. 

<b> Exhaustive coverage of the most commonly used words, sorted according to frequency</b> – includes over 2,700 words and 1,300 kanji, covering 80%–90% of all the words and kanji most commonly used in everyday life and popular media.

<b> Natural example sentences </b> – all with full audio and furigana, including a lot of common idiomatic expressions and non-textbook grammar.

<b> Beginner-friendly grammar </b> – most of the sentences use only N5–N4 grammar, with added explanatory grammar notes.

<b> The deck is also available with word furigana + audio on the front (with optional romaji field) </b> [You can download the two versions of the deck on the releases page.](https://github.com/fafner8/Manabi/releases/)

Additional features: normalized audio loudness, specifically marked common する verbs and な adjectives, and all new vocabulary highlighted inside the sentences like in Kaishi.

*The example sentences sometimes make use of easily recognizable English-derived katakana words without introducing them in dedicated cards (but some harder katakana words get their own cards).

Card front & back format:
<img width="1283" height="667" alt="deck1" src="https://github.com/user-attachments/assets/42a26376-eb2a-4993-8066-71cc2230ef78" />

Card front of the kana deck:

<img width="643" height="292" alt="deck2" src="https://github.com/user-attachments/assets/1371c14f-3a06-4258-ab05-fc6858b4f686" />

## How to use this deck

The deck presupposes the ability to read hiragana & katakana, and it’s also highly recommended to learn about particles and basic conjugations before doing the deck (or at least study the relevant grammar points as you go). The vast majority of the sentences in the deck only use N5-N4 grammar, and I specifically tried to keep the sentences as short and grammatically simple as possible, with occasional brief notes added to explain grammar points which might confuse beginners.

The deck is also not a substitute to immersion, and you should start immersing as early as possible (or at least after finishing the first 1k cards or so), as immersion helps to reinforce the vocabulary learned through SRS. I believe the advantage of a core deck is that it removes the pressure from needing to mine unknown words which can be very overwhelming in the beginner stages (but you can also use a separate mining deck alongside Manabi, if you find that effective).

The deck comes in two versions: the first is kanji oriented (it has only the word in kanji on the front) and the second version focuses on vocabulary and adds furigana and word audio on the front (so you only need to recall the English definition). You can choose either, depending on your learning style and priorities. Both decks include the example sentence on card front like Kaishi does, but the sentences can easily be removed by editing the card's front template (see below).

I would personally recommend to not read the example sentence before attempting to recall the word’s meaning, in order to avoid memorizing the sentence instead of the word. It goes without saying that you are much more likely to be able to recall the word’s meaning and reading ‘in the wild’ if you can recall it without having to see the example sentence. But this doesn’t mean the example sentences are useless, because they can help you understand how the word is used in context and its grammatical role. Additionally, the sentence can serve as a mnemonic if you are able to associate the sentence with the word and recall the sentence (from memory) when you see the word, serving as a reminder for the word’s meaning.


To remove the front sentence go to tools -> manage note type - > select Manabi from the list -> cards -> and in ‘front template’ remove the line that contains {Sentence} (or {furigana:Sentence Furigana} in the kana deck).

## Why this deck was created, and how it differs from other core decks

Kaishi 1.5k is currently the most popular beginner deck (and deservedly so), but although it’s very well-put together, it still falls short in several respects which I believe justified making yet another core deck (see below). For this reason, the deck is not just a fork or expansion of Kaishi but was built from scratch, with everything being newly reordered, and a lot of added new sentences and audio from sources that weren’t used by Kaishi (including in the first 1.5k words). There’s still naturally a lot of overlap with Kaishi because the deck, just like Kaishi, draws from the same pool of sentences from the core 6k & Tango decks (which ultimately come from the iKnow website) since they have high quality audio recordings by professional voice actors.

The deck attempts to solve two main problems which I found with Kaishi:

The first issue is the fact that the example sentences used by Kaishi often introduce unknown words (or worse, unknown kanji), that is, words that haven’t been taught in previous cards (the so-called N+1 or i+1 principle), something that seriously undermines the usefulness of the example sentences. With very small exceptions, Manabi strictly follows N+1, and goes even further by trying to do the same with regard to kanji. For example, one of the earliest words that Kaishi teaches is 勉強 (card 10), but not only is the word not in the top 10 most used words, there are other words you could introduce first (like 強い), before introducing the two kanjis all at once. Whenever possible, I tried to avoid introducing 2 new kanjis per card, and as a result, only 70 cards in the whole deck introduce 2 new kanjis at once, and no single card introducing more than 2 new kanjis.

The second main issue I wanted to address is word selection and ordering. Kaishi already has pretty good vocabulary selection, but it’s just too small to be a true ‘core’ deck, lacking in some important high frequency words, while introducing lower-frequency words too early. To give you an idea, over a third of Manabi’s first 1,500 words were not included in Kaishi, and many of the words in Kaishi were moved to a lower rank in Manabi (while some words from Kaishi didn’t even make it into the deck, despite its size, because they were too low-frequency.) 

To my knowledge, the creators of Kaishi relied on a single frequency list (JPDB) which is too heavily  skewed towards anime (and also had some strange rankings even compared to other frequency lists based on anime), and to achieve a better word selection and ranking, my approach was to rely on several frequency lists drawn from different kinds of sources: Netflix subs, captions from easy Japanese YouTube channels, SOL anime, and unscripted conversations, in order to achieve a balanced and exhaustive selection of words found both in fictional media and naturally spoken language. This is important because when you examine different frequency lists, there’s a group of around 2,000 words that consistently comes on top, and which account for between 80% and 90% coverage of all the vocabulary most frequently used in everyday life and popular media. This is the reason I made the deck larger than Kaishi. The first 2k words will cover pretty exhaustively the vocab most commonly found in casually spoken language and relatively easy-level anime (e.g. slice-of-life). The last 700 words aim to expand the coverage for more advanced types of content. The deck will also teach you 1,300 kanjis which will give you similar percentage of coverage for the written language (between 80% and 90%).

Another relatively small issue in Kaishi is poor audio quality for some words and sentences. I tried to find better audio recordings whenever possible, and particularly word audio was carefully selected from the best available sources, improving upon the audio in Kaishi for a large number of words.

## How this deck was made

The majority of the sentences and audio used in the deck come from the old core 2k6k decks (which originate from the iKnow website). Additional sentences came from multiple other decks taken found in ankiweb (credited below), and occasionally anime and video games. The basic vocabulary selection and English translations were taken from the core 6k and Kaishi 1.5k decks. This however was only the starting point and the selection of vocabulary was greatly expanded using other sources like frequency lists. The English translation were in many cases improved when needed, primarily by consulting Jisho. The final ordering of the cards is a result of complicated balancing between frequency ranking and constrains from available example sentences for a given vocab.

Some of the frequency lists I used to order the cards are: [Netflix](https://docs.google.com/document/d/1IUWkvBxhoazBSTyRbdyRVk7hfKE51yorE86DCRNQVuw/edit?tab=t.0](https://docs.google.com/document/d/1IUWkvBxhoazBSTyRbdyRVk7hfKE51yorE86DCRNQVuw/edit?tab=t.0)), [anime](https://docs.google.com/spreadsheets/d/1xeG-b85EHwo-yUDgwDLuWyYdwtnDgJAzr3VTmteMOaA/edit?gid=1886769620#gid=1886769620), [Jo-Mako's Japanese Guide](https://docs.google.com/spreadsheets/d/1z3Wc85VuDhjgjy1s_zgbGx2daaOoqm0s/edit?gid=893750221#gid=893750221). Other lists I generated myself using YouTube captions from easy Japanese channels and SOL anime.

Nothing in this deck is AI generated, except when I relied on AI to help me build various python scripts for ordering the cards, generating furigana and proofing. The furigana was generated using Mecab + UniDic + JMdict (and then checked and proofed). 

I’m the only person who’s been involved in making this deck (aside from small consultations), so if you wish to volunteer to help me further proof the deck you can contact me at fafner1988@gmail.com 

# Credits

The example sentences and audio recordings were taken from the following decks: Core2k6k, Core10k, Tango, Kaishi 1.5k, 4,217 Japanese Sentences, glossika, A Frequency Dictionary of Japanese, JLPT N5 Kanji JPod101, jpdb, and a few anime, video game and TV shows soundtracks.

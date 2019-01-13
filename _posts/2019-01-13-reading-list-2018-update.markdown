---
title: "2018 Reading List Recap/Update"
layout: post
tag: books
img: indigo/indigo.png
projects: true
draft: true
author: artiannaswamy
summary: "Update on 2018 Reading List"
permalink: reading-list-2018-update
jemoji: '<img class="emoji" title=":books:" alt=":books:" src="https://assets.github.com/images/icons/emoji/unicode/1f4da.png" height="20" width="20" align="absmiddle">'
---

<h2 class="title">Previous reading list posts</h2>

- <a href="http://artiannaswamy.com/reading-list-2016" target="_blank">2016 Reading List</a>
- <a href="http://artiannaswamy.com/reading-list-2017" target="_blank">2017 Reading List</a>
- <a href="http://artiannaswamy.com/reading-list-2017-update" target="_blank">Update on 2017 Reading List</a>

## Index
- [New in Reading Tech](#newtech)
- [Books & Long-form Reads](#read)
- [Audiobooks](#audio)
- [Abandoned](#abandoned)

---

<div class="breaker"></div><a id="newtech"></a>
<h2 class="title">New in Reading Tech</h2>

A few more items that rocked my world with respect to reading. For last year's list, see <a href="http://artiannaswamy.com/reading-list-2017-update#newtech" target="_blank">New in Reading Tech in 2017</a>.


<h3>The year I discovered Audiobooks</h3>

By a series of serendipitous events, I came to listen to <a href="https://www.audible.com/pd/Born-a-Crime-Audiobook/B01IW9TQPK?qid=1547392465&sr=sr_1_1&ref=a_search_c3_lProduct_1_1&pf_rd_p=e81b7c27-6880-467a-b5a7-13cef5d729fe&pf_rd_r=6QM1M1MTFWBTB56Q39SM&" target="_blank">Born a Crime</a> by Trevor Noah (Daily Show) at the same time as two of my coworkers, and it turned into the most wonderful, impromptu audio book club and made me a forever fan of audiobooks.

Following Born a Crime, I've listened to 6-7 more audiobooks and that is a medium now firmly part of my reading experience. 

For any other readers looking to wade into audiobooks, a couple of observations below:

- An excellent narrator will elevate even a mediocre book, and a narrator you don't like will turn you against your favorite book. I have never relied too heavily on reading book samples before buying or borrowing a book, but I learned my lesson with audiobooks early on. Listen to the full 5 minutes of the sample and imagine hanging out with this person for the entire length of the book (often 8 hrs to 21 hrs depending on the subject), and then commit to it. Luckily, Audible has a fairly generous return policy and I was able to return a couple of books with narrators I didn't like.

- Certain topics seem to lend themselves better to an audio format. This is of course dependent entirely on personal taste and preference, but I gravitate towards memoirs and science fiction in audio format and prefer other genres like literary fiction, business / psychology, self-help,  etc. in e-book format. Books read by authors are a risky move as book narration is more performance than reading, but when the authors themselves are actors/comedians, it lands well. Memoirs read by the authors had an especially powerful impact (Born a Crime by Trevor Noah, The Year of Yes by Shonda Rhimes), while science fiction / fantasy read by a professional narrator or performer (Ready Player One, Armada by Wil Wheaton, Martian by R.C. Bray, Anansi Boys by ? etc.) worked well.

- The pacing of the plot is an important consideration. It is difficult to skip ahead in an audiobook, unlike an ebook, so if the plot doesn't move along at a clip, it feels like the book simply won't end. This is difficult to tell from the sample. I haven't yet found a solution to this other than to read the reviews carefully.

- I've found several options to get audiobooks - from libraries (via Libby), Audible, Kindle WhisperSync narration to add to books you already own etc. Audible is worth the default Gold plan at $15/month for one credit (worth one book) because they have excellent customer service, a fairly generous return policy, and sufficient perks/sales/free content to keep you engaged after you have used up the single credit. There is also an option to pause the subscription for up to three months every year, and a <a href="https://lifehacker.com/the-best-audible-tips-and-tricks-you-might-not-know-abo-1792389233" target="_blank">hidden silver plan</a> that offers one book every two months for the same $15/credit. You also own all books you purchase even if you cancel the subscription, unlike songs on a streaming audio service.


<h3>Checking for Goodreads books on Overdrive</h3>

Goodreads has been a trusty companion these past three years as I have rediscovered reading. After years of tracking potential books to read in Word documents, on my iPhone, on Evernote etc., my system now is fairly simple: I hear about a new book on NPR, on a podcast, in a newsletter, or from a friend, look it up on Goodreads and add it to my 'Want to Read' shelf, and tag it to my current year reading list.

This has the benefit of maintaining a single comprehensive reading list, accessible via multiple mediums, and providing additional reviews and links I can use to decide if I want to read the book.

Where this process has occasionally gotten clunky is when it is time to actually buy / borrow the book. I am a huge fan of libraries, and with Overdrive making it so easy to borrow a book, I like to borrow them when I can. The most user-friendly way to search Overdrive has been via the Libby app on my phone - I have more than one library card, and Libby looks the book up in all libraries you have access to and borrows the book wherever it is available.

The process, although clunky, works great as long as I am looking up a couple of books at a time. But, come the holidays or any kind of vacation, I stock up on 5-10 books to read on the flights and in hotel rooms, and this is where the Libby lookup process becomes time consuming.

After recently returning from a vacation where I read quite a few books but had to spend quite a bit of time and thumb power looking up all the books on Libby, I decided to flex my Python skills to build such a solution if one didn't exist. Luckily, someone has already found a way and built a helpful Chrome add-in. 

The add-in is easy to add to your browser, easy to configure and very effective at a glance.

<Add link>


<h3>Adding books to Goodreads from an Amazon page</h3>

Most online articles link directly to the Amazon page of a book, and it has been easy to add the book to one of my Amazon lists for tracking. This inevitably causes two separate book lists that I end up having to merge periodically. Given that Amazon owns Goodreads, I expected an easier way to just 'Share' the book to Goodreads from the Amazon page or even add to one of the Goodreads shelves directly from the 'Add to List' menu. Unfortunately, I haven't managed to find any such button or any Chrome add-in to hack in this functionality.

Once again, the internet comes to the rescue. This is a <a href="https://gist.github.com/lightningdb/cfee260c3b7af7e65fce" target="_blank">javascript snippet</a> that can be added to any browser as a bookmark: it launches the Goodreads site on a new tab and searches for the title of the book you currently have open on Amazon. It has not failed me yet for mainstream, English-language titles.



---

<div class="breaker"></div><a id="read"></a>
<h2 class="title">Books & Long-form Reads</h2>

<h3>1. Neverwhere by Neil Gaiman</h3>	
<iframe type="text/html" width="336" height="550" frameborder="0" allowfullscreen style="max-width:100%" src="https://read.amazon.com/kp/card?asin=B000FC130E&preview=inline&linkCode=kpe&ref_=cm_sw_r_kb_dp_yW0oCbYQDWESG" ></iframe>





---

<div class="breaker"></div><a id="audio"></a>
<h2 class="title">Audiobooks</h2>

<h3>1. Ready Player One and Armada by Ernest Cline</h3>
<div><script src="https://www.overdrive.com/media/3036595/sample-embed?slug=ready-player-one"></script></div>
Audible - Ready Player One: https://www.audible.com/pd/Ready-Player-One-Audiobook/B005FRGT44?qid=1547390429&sr=sr_1_1&ref=a_search_c3_lProduct_1_1&pf_rd_p=e81b7c27-6880-467a-b5a7-13cef5d729fe&pf_rd_r=ACP9V390PCDCRZCQRQBM&

<div><script src="https://www.overdrive.com/media/2122540/sample-embed?slug=armada"></script></div>
Audible - Armada: https://www.audible.com/pd/Armada-Audiobook/B00VN0Q8XY?ref=a_pd_Ready-_c5_lProduct_1_1&pf_rd_p=65d90c29-eff1-4be3-9785-6ed41e3e7842&pf_rd_r=QFFQFYBSYP9VAGTT322D&

<h3>2. Anansi Boys by Neil Gaiman</h3>	
<div><script src="https://www.overdrive.com/media/79161/sample-embed?slug=anansi-boys"></script></div>

---
<div class="breaker"></div><a id="reading-list"></a>
<h2 class="title">Books started in 2017</h2>

<h3>8. What If?: Serious Scientific Answers to Absurd Hypothetical Questions by Randall Munroe</h3>
<iframe type="text/html" width="336" height="550" frameborder="0" allowfullscreen style="max-width:100%" src="https://read.amazon.com/kp/card?asin=B00IYUYF4A&preview=inline&linkCode=kpe&ref_=cm_sw_r_kb_dp_JeCIAbKEW0MD0" ></iframe>
Ever wanted to get fully thought out, scientifically precise answers to questions like "What would happen if the earth stopped spinning?" or "What happens if everyone in the world gathers in one place and jumps together?" or "How big does a laser pointer have to be to heat the moon?". No? Well, don't be so sure. I'm halfway through this book and thoroughly enjoying the thoroughly researched scenarios that I never gave a thought to before now.

<h3>9. Death by Black Hole: And Other Cosmic Quandaries by Neil deGrasse Tyson</h3>
<iframe type="text/html" width="336" height="550" frameborder="0" allowfullscreen style="max-width:100%" src="https://read.amazon.com/kp/card?asin=B000XPPVCY&preview=inline&linkCode=kpe&ref_=cm_sw_r_kb_dp_YlCIAbXYRGGBY" ></iframe>
Similar to the above but more galactic and comprehensive, and more patiently explained by Neil deGrasse Tyson. Enjoying this so far.

<h3>10. The Underground Railroad by Colson Whitehead</h3>
<iframe type="text/html" width="336" height="550" frameborder="0" allowfullscreen style="max-width:100%" src="https://read.amazon.com/kp/card?asin=B01A4ATV0A&preview=inline&linkCode=kpe&ref_=cm_sw_r_kb_dp_oqCIAb3DNQHET" ></iframe>
So far, it has been a sprawling portrait of one woman as she silently bears life on the plantation. The eBook expired before I could finish it, but I will definitely re-borrow when I have some time to dedicate to the book.

---
<div class="breaker"></div><a id="abandoned"></a>
<h2 class="title">Books I abandoned</h2>


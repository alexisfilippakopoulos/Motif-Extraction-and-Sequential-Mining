# Motif-Extraction-and-Sequential-Mining

Working on an artificial tinder messages dataset to extract frequent message sequences and visualize the conversation endings (last 6 messages sequence). 

The columns that intereset us:
* conversationid : id of the conversation in which the message can be found
(two users per conversation)
* message.type : We have built a typology of messages to help you look for
patterns. This where we introduced patterns.
enumerate

We defined the following mutually exclusive message types :
1. aff.norm : text with normal affirmative sentences, without a question mark,
without offensive words, not too many words
2. chunk : text with normal affirmative sentences, without a question mark,
without offensive words, but with higher number of words
3. questn : there is a question mark in the text
4. aff.off : text with normal affirmative sentences, without a question mark,
not too much text, with offensive words/emojis (insults, strong words, etc).
5. phone : a phone number is exchanged
6. piss.off : one of the users tells the other to stop sending messages, in a not
so polite way
7. end : polite message in which a user says that the conversation should stop,
without exchanging phone numbers

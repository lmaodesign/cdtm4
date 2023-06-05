# Cat Database Training Model IV (CDTM4)
From now on, chat mentions for user TehNeon must be cross-checked by Cat Database Training Model IV (CDTM4). If the cross-check yields a confidence level of ~0.75 or above, the chat is deemed as a valid chat mention.

## More information on CDTM4:
Cat Database Training Model IV (CDTM4) is an advanced chat extraction tool. CDTM4 has been trained using more than 10,000 annotated chats. It aims to be robust and easy to use for both human and algorithmic annotators.

The Chat Database can be retrieved in two different ways:
Direct access - The chat database can be directly accessed using this url: http://www.cat-db.com/chat/chat_download/
- The chat database can be directly accessed using this url: Chat database with annotations - The chat database can be downloaded together with annotations. This feature is only available for chat mentions in the Cat Database. It is not available for the rest of the cat corpus (Cat Database Training Data and Chat Corpus), see: http://www.cat-db.com/documentation/#cat-db-training-data-and-chat-corpus

The following options are available:
- Download annotated chat database (csv file) - A chat database is available in the following format: for example, 'a_123,b_123,c_123,d_123'.

  - A chat database is available in the following format: for example, 'a_123,b_123,c_123,d_123'. Download annotated chat database with annotations (txt file) - A chat database is available in the following format: for example, 'a_123,b_123,c_123,d_123' and 'type'='chat'. The type will be the type of the chat mention, for example, 'mention' for a chat mention.

  - A chat database is available in the following format: for example, 'a_123,b_123,c_123,d_123' and 'type'='chat'. The type will be the type of the chat mention, for example, 'mention' for a chat mention. Export annotated chat database to another (csv file) - A chat database is available in the following format: for example, 'a_123,b_123,c_123,d_123' and 'type'='chat'. The type will be the type of the chat mention, for example, 'mention' for a chat mention.

All the annotated chat mentions are now exported to Cat Database Training Model IV (CDTM4). The annotation for CDTM4 is an 'a' annotator. You can download the chat database with annotations to your own local machine. You can modify your annotations and apply them to your chat corpus.

CDTM4 supports four common annotation categories: mentioned, paraphrase, mention, and paraphrase. The category will be added to the chat mentions. All annotators are trained to use the new category. To access the chat database with annotations, go to the Cat Database Training Model IV.

**Important Note:** The chat database with annotations can be used only to train CDTM4 and other chat extraction tools. The chat database with annotations is not intended to be used directly for chat detection in your own application.

# Listeos
Listeos is a discussion website that uses the EOS blockchain to comment, vote, and reward users. To view the project, visit https://listeos.com

![Listeos Home](https://github.com/crypto5000/listeos/blob/master/img/listeos.gif)

# Comments
Comments are starting responses to the topic. To comment, you send an EOS transaction from a wallet. The transaction must: 1) be sent to the Topic ID address; 2) contain the specified EOS amount; 3) include a text memo. The "memo" field is the text that gets displayed on Listeos as your comment. The account you send "from" becomes your username displayed next to the comment.

# Replies
You reply to starting comments or other replies. Replies take the same form as comments EXCEPT the memo field requires a special starting code. The memo field must start with an id, followed by a colon ":". An example memo, would be "90c17b59: This is my reply". In this example, the text "This is my reply" would be displayed.

# Upvotes #1
Upvotes push comments or replies higher. To upvote, you send an EOS transaction from a wallet. The transaction must: 1) be sent to the Topic ID address; 2) contain the specified EOS amount; 3) include a specially formatted memo. The memo field must start with an id, followed by the text ":up". An example memo, would be "90c17b59:up".

# Upvotes #2
Upvotes push comments or replies higher. To upvote, you send an EOS transaction from a wallet. The transaction must: 1) be sent to the user's address being upvoted; 2) contain the specified EOS amount; 3) include a specially formatted memo. The memo field must start with the topic ID, followed by a colon ":", followed by the "up", followed by a colon ":", followed by a unique id. An example memo, would be "aaaaaaaaaaaa:&#8203;up&#8203;:90c17b59".

# Downvotes
Downvotes push comments or replies lower. To downvote, you send an EOS transaction from a wallet. The transaction must: 1) be sent to the Topic ID address; 2) contain the specified EOS amount; 3) include a specially formatted memo. The memo field must start with an id, followed by the text ":down". An example memo, would be "90c17b59:down".

# Wallets
Listeos works with EOS transactions. So any wallet or EOS tool that allows you to transfer EOS should work with Listeos. You just need to be able to type the appropriate text into the "memo" field of the transaction. It's also possible to send from an exchange - assuming the exchange doesn't have a minimum withdrawal limit. If you send from an exchange, your displayed username is the exchange's wallet address.


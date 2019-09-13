# internet_relay_chat_bot
This is an internet relay chat bot which when attached to any channel on freenode.net, will reply to messages directed towards bot.

Project video - https://youtu.be/2vj3cEjLI3I

Aside from managing channel permissions, a bot can also perform functions such as logging what is posted to an IRC channel, giving out information on demand (very popular in IRC channels dealing with user support), creating statistics tracking the channel's top posters and longest-lived lurkers, or hosting trivia, Uno and other games. These functions are usually provided by scripts, often written in a scripting programming language such as Tcl or Perl by the bot's users. Channels dedicated to file sharing often use XDCC bots to distribute their files.

Algo:-

1.We will first knock out the simple items by addressing the global variables/settings for our IRC bot. 
2.We will then build a quick function to select quotes.
3.Then we make the bot module by first creating a class to create bots (a factory class), and then another class to define the behavior of the bot. 
4.We will also write a quick plugin to easily create and start up our bot from the command line. 
5.Lastly, we will write tests for the expected behavior of our talkback bot application.

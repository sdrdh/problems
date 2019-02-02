# Message Box

You have to create a message box which should be like a common message box between many people who can communicate to each other only through the message box.

Write a python command line application which can take commands like
```shell
> python message_box.py sendmsg user1 user2 msg # Should send the message msg to user2 from user1
> python message_box.py getunread user1 # should get the messages for the user1 should only show the unread messages
> python message_box.py getall user1 # should show all the messages read or unread
> python message_box.py getunread user1 user2 # should get the unread user1 messages sent from user2
> python message_box.py getall user1 user2 # should get the all the user1 messages sent from user2 
```

The app need not be a client-server kind of application.

A message is considered read when the user2 gets the messages
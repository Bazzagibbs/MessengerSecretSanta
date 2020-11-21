# Facebook Messenger Secret Santa

## NOTE: fbchat is broken. To fix, delete line 190 in fbchat/_state.py, and replace with "revision = 1"


This is a tool used to generate secret santas over Facebook Messenger.

Usage:          
python secret-santa.py [-options]

Options:
* -h            Help: display this message.
* -s              Select: choose to include or exclude specific people in the group.
                You will be prompted to choose before messages are sent.
* -t              Test: print out results instead of sending messages to participants.
* -m              Message: customize the message to send to participants.

To use this program, you will be prompted to log in with a Facebook account. Don't use your main account if you are participating in the Secret Santa. You will then need to provide a Group Chat ID:
        
        messenger.com/t/<this-is-the-group-chat-id>
This group should have all the participants of the Secret Santa and the host account.

If the [-t] option has been set, a randomised list of participants will be printed. Otherwise, each participant will be sent a message with their Secret Santa and the results will not be printed.

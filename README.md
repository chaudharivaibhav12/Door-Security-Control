# Door-Security-Control

## Description

This system controls the opening and closing of a door based on password entry. If the password is correct the person can enter. Each person is given two chances to enter the correct password. On failure, an alarm is sounded. Inside the room a button is available. When the button is pressed the door opens for 1 Min, so that the person can leave the room.

## User Interface

There are three set of passwords:
1. User Password
2. Master Password
3. Alarm Password

- The Master password is used by the security Personnel for updating Password of the day. Pressing the M button activates this mode. The system glows ‘Enter Password’ LED asking the personnel to enter the password. The master password is a 16-digit value. The master is given only a single chance to enter the password.

- If authenticated, the retry/Update LED glows. If there is a failure in authentication the alarm is sounded.

- When the retry/ Update LED glows the user has to enter password of the day. This is 12-digit value. Once this value has been accepted by the system the ‘Passwd Updated’ LED glows.

- User has to press the O key when he wants to enter the room. The Enter Password LED prompts the user to enter the password. The user is given C/AC option as well. If the first attempt fails, the RETRY LED glows. The user is allowed to re-enter password, on authentication door opens for a period of 1 Min. On Failure an ALARM is sounded.

- To Turn-off the Alarm the A button has to be pressed. ‘Enter Password’ LED glows prompting user to enter the 14-digit password for turning of alarm, no retries are allowed. If authentication is successful then the alarm is turned off.

- To leave the room a button is available inside the room, when the button is pressed the door opens for 1 Minute so that the person can leave the room.



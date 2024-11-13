+++
title = 'Recurisve Thinking'
date = 2024-08-08T19:25:32+01:00
draft = true
+++

# Try harder
Often in offensive security if you can't find any vulnerabilities, just **try harder**. It's like people who ask a question that can easily be Googled, they should try harder.
This mentality is a necessity because hacking isn't just about knowing, it's learning and seeking for what you need. 

# Recursion
Think of physical security of a barrier at a subway/tube station. You tap your card, door opens, you move forward, it closes.
Pretty high level but working with that is too little, too vague.

Break it down

1. Tap your card.
2. Sufficienct Balance? If no, decline
3. If yes. Open
4. Wait till the person has walked past
5. Close

Break it down again

1. Tap your card.
2. Sufficient balance? If no, decline
3. If yes. Open
4. Sensor checks if the person has walked past
5. The sensor waits a maximum of five seconds
6. Has the sensor been tripped and for how long?
7. If it's rather long can we close it?
8. If the person has passed, close it


Again it can be broken furhter with more information about the card

Breaking it recursively allows us to review each step, each detail. It makes sure we cover every area and that is crucial in security. Often people will try to get past barriers with methods such as tailgating. Breaking it down helps us see that such as step 6, it also helps us to see what is enforced, what if the sensor waits longer than five seconds if it's blocked, can someone just cover it?

Is it enforced?
Is it as intended?
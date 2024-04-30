---
layout: essay
type: essay
title: "E5: Reflecting on Assignment 2 Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2024-04-12
published: true
labels:
  - Assignment 2
  - E5
  - Learning
---

## 1. Provide a brief introduction to the assignment along with a link to this page for further details 
For this assignment, we were supposed to add to our Assignment 1. We added login and registration pages that are supposed to appear before the invoice page so that the user cannot purchase anything until they have logged in. These pages were supposed to be linked to a user.json file so that when the login form is submitted, it checks that the user's information is correct. It also adds the information from the registration to the user.json. The most important part was finding a way to carry the quantities over through the query string across all pages. Click [Assignment 2 instructions](https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2.html) to see more detailed instructions. 

## 2. What did you learn from this assignment?
I learned more about the difference between server-side and client-side data and that it is really important to know what information is accessible to each one. I also learned about how all the pages are linked together through the server. I learned how query strings work and that things can be added to it to carry across pages.

## 3. Did you work with a partner? Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself).
I did not work with a partner. I did all of it by myself.

## 4. How did you get help when you needed it? What did you need help with?
I utilized ChatGPT a lot and it helped for the most part, but not for carrying the quantities in the query string. I had initially used localStorage, which was suggested by ChatGPT, but I started running into more problems. After trying to fix it myself and with more GPT, I decided to ask Professor Port. He was very blunt in the fact that ChatGPT was not giving me the best possible solutions, but he was able to fix it for me in an hour when I had been trying for 3 days. Other parts that I needed help with were getting my login and registration info to be sticky when there were errors. For this, I used ChatGPT and asked some friends, and I was able to do it. For the error messages, I referred to how the errors were posted on the store.js.

## 5. How was developing this assignment different than assignment #1?
This dealt with a lot more javascript and really having to understand about the query string and the app.post. It made me think a lot more about exactly what I wanted to do and how I could do it without hardcoding. It also required a better understanding of what is server-side and what is client-side because you can't access certain things, which makes you change the approach. 

## 6. Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging
I would say I spent a total of like 2 days thinking about how to do things because I kept getting stuck and trying to figure out where it went wrong. Roughly another 2 days writing code because I would always have to edit and fiddle with things to see what would work. I think the bulk of my time was testing and debugging, so maybe 3 days to do that. I'm not sure about hours, but I must have spent at least 50 hours coding.

## 7. Describe what worked well with this project? What did not work well?
The login.html and registration.html went well. I was able to finish that rather quickly, especially because we did some of it during lab. I think that gave me the least amount of trouble, with the error messages, adding new users to the file, and checking user info in the file. The quantities in the parameters did not work well at all. I had such a hard time that I didn't even understand what I did anymore, which is why I asked Professor Port. The decreasing quantities after login also did not go well because I kept getting errors. 

## 8. If you could go back in time and do things differently, what would you do differently?
I would start earlier. Once I finished Assignment 1, I should have already been starting on Assignment 2 and thinking about how I would do it. I would also ask for Professor Port's help earlier. If I did, I wouldn't have been stuck on the query string for 3 days because he fixed it so fast. 

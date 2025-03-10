# Reflection

Student Name:  Solomon Burt
Sudent Email:  sdburt@syr.edu

## Instructions

Reflection is a key activity of learning. It helps you build a strong metacognition, or "understanding of your own learning." A good learner not only "knows what they know", but they "know what they don't know", too. Learning to reflect takes practice, but if your goal is to become a self-directed learner where you can teach yourself things, reflection is imperative.

- Now that you've completed the assignment, share your throughts. What did you learn? What confuses you? Where did you struggle? Where might you need more practice?
- A good reflection is: **specific as possible**,  **uses the terminology of the problem domain** (what was learned in class / through readings), and **is actionable** (you can pursue next steps, or be aided in the pursuit). That last part is what will make you a self-directed learner.
- Flex your recall muscles. You might have to review class notes / assigned readings to write your reflection and get the terminology correct.
- Your reflection is for **you**. Yes I make you write them and I read them, but you are merely practicing to become a better self-directed learner. If you read your reflection 1 week later, does what you wrote advance your learning?

Examples:

- **Poor Reflection:**  "I don't understand loops."   
**Better Reflection:** "I don't undersand how the while loop exits."   
**Best Reflection:** "I struggle writing the proper exit conditions on a while loop." It's actionable: You can practice this, google it, ask Chat GPT to explain it, etc. 
-  **Poor Reflection** "I learned loops."   
**Better Reflection** "I learned how to write while loops and their difference from for loops."   
**Best Reflection** "I learned when to use while vs for loops. While loops are for sentiel-controlled values (waiting for a condition to occur), vs for loops are for iterating over collections of fixed values."

`--- Reflection Below This Line ---`

I was glad we already made the packaging module. It made the parsing logic way easier. I just had to figure out how to call the functions and display the results. This was a good intro to Streamlit and the core functionality. I felt like I was making progress, and seeing the output was satisfying. Then came the file processing. That's when things got a little more complicated. File uploads, reading line by line, and then saving the parsed data as JSON? My brain started to hurt a bit. I was a little nervous about the JSON output, but the json.dump function made it relatively straightforward. When I saw the 'session state' requirement, I was initially confused. But after reading the Streamlit docs, I realized what is was supposed to do. Keeping track of the file and line counts across multiple uploads is much better with session state. It made the program more user friendly. Seeing the summaries displayed after each upload was really interactive. I learned that breaking down a complex problem into smaller, manageable parts is crucial. It made the whole process less overwhelming. I really liked using streamlit
Password Strength Evaluation 
================================================================

Tool Used:
----------
- Website: Password Monster (https://www.passwordmonster.com/)
- Purpose: To evaluate password strength based on length, complexity, and entropy

Steps Followed:
---------------

1. **Password Creation**  
   - Created a variety of sample passwords with varying complexity:
     - Short and simple (e.g., "password")
     - Moderate (e.g., "Password123")
     - Complex (e.g., "P@ssw0rd!")
     - Passphrase-style (e.g., "L!tt13_Blu3_H0rse")
     - Completely random (e.g., "X9m$4P&1Zbq!w")

2. **Password Testing on Password Monster**
   - Entered each password into the Password Monster tool.
   - Observed the real-time feedback, including:
     - Estimated time to crack the password
     - Strength meter (weak, fair, strong, very strong)
     - Visual indicators (color-coded feedback)
     - Suggestions for improvement

3. **Recording Results**
   - Took note of each password’s strength level and time-to-crack estimation.

4. **Analysis**
   - Compared simple vs. complex passwords to understand what contributes most to strength.
   - Identified common weaknesses flagged by the tool (e.g., using dictionary words, short length).
   - Used the insights to extract general best practices and tips.

5. **Results**
   - Summarized results in a table format: 

| Password            | Strength Rating | Time to Crack | Feedback                                |
| ------------------- | --------------- | ------------- | --------------------------------------- |
| `password`          | Very Weak       | 0 second      | Too common, avoid dictionary words      |
| `Password123`       | Very Weak       | 0 second      | Predictable pattern                     |
| `P@ssw0rd!`         | very Weak       | 0 second      | Better, but still resembles common word |
| `L!tt13_Blu3_H0rse` | Very Strong     | 12 hours      | Good use of symbols and passphrase      |
| `X9m$4P&1Zbq!w`     | Very Strong     | 5 billion yrs | Excellent entropy                       |
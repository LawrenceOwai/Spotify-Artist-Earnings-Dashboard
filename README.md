🎧 Spotify Artist Earnings Dashboard — Cool, Simple and insightful💸🎶

Ever asked yourself:
“How much is my favorite artist really making from all those streams?”
Well, I built a Demo Power BI dashboard that answers just that — and more — in the most interactive and engaging way possible.

One of my favorite features in this dashboard is the real-time greeting — it tells you “Good Morning, Davido” or “Good Evening, Wizkid” based on your system time and the artist you select. Built with a simple DAX formula using HOUR(NOW()) and SWITCH(), it updates automatically as the day or artist changes. It’s not just data — it’s data that feels alive.

Welcome Text = 
VAR Hours= HOUR(NOW())
VAR Greetinggs= 
    SWITCH(
        TRUE(),
        Hours >=0 && Hours <12, "Good Morning",
        Hours >=12 && Hours <4, "Good Afternoon",
        Hours >=4 && Hours <24, "Good Evening"
    )
    RETURN
    Greetinggs & " " & SELECTEDVALUE('Sheet1'[Artist])
    

If you’re a data lover, music enthusiast, or just curious about how dashboards can drive decision-making in the entertainment industry — this one’s for you! 🎤



https://github.com/user-attachments/assets/6fb8a71f-9b6b-4fef-be31-a422d238c54a

![Screenshot 2025-06-28 220311](https://github.com/user-attachments/assets/c2f9d5e6-e722-4ddb-9b1a-5cf6540b02b3)
![Screenshot 2025-06-28 220433](https://github.com/user-attachments/assets/a2767fd0-0cc5-4cf2-b78d-ea01739df537)

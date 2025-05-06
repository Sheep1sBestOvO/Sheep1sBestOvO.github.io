# 🎵 Jay Chou Tribute Website Documentation

## 📎 Deployed Site  
[http://127.0.0.1:3000/index.html](http://127.0.0.1:3000/index.html)

---

## 📝 Project Summary  
This is a tribute website to **Jay Chou**, showcasing his iconic albums and songs. The homepage displays his albums in a horizontally scrollable layout, and each album links to a dedicated page with a representative song, lyrics, and themed visuals. The site includes interactive JavaScript features like rotating album covers and song players to enhance the fan experience.

---

## 📸 Screenshot of page
![Screenshot of Jay Chou site](assets/jay_main.png)  

---

## 💻 Code Snippet + Explanation  
```javascript
lyricsDiv.textContent = "";
lyricsDiv.classList.remove("hidden");
toggleBtn.textContent = "Hide Lyrics";
typedIndex = 0;

typingInterval = setInterval(() => {
  if (typedIndex < lyricsText.length) {
    lyricsDiv.textContent += lyricsText[typedIndex++];
  } else {
    clearInterval(typingInterval);
  }
}, 80);
```
This snippet taught me how to implement a typing animation effect using setInterval and dynamic DOM manipulation. I learned how to:

Control and gradually build up text output using JavaScript


Dynamically update UI elements like buttons and containers

Improve user interactivity and experience using simple JavaScript logic


## Note 

What I Struggled With
Fine-tuning the timing and smoothness of the typing animation

Ensuring lyrics displayed and hid at the right time

Making the layout responsive across screen sizes


What I Would Add Next
Pause/resume functionality for the typing animation

Syncing lyrics with actual audio playback






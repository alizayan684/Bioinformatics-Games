# 🧬 Local Alignment Game - README

Welcome to the **Local Alignment Game** - where bioinformatics meets fun! This interactive tool helps you understand the Smith-Waterman algorithm for local sequence alignment through hands-on visualization.

## 🎮 What's This About?

This game demonstrates how local sequence alignment works in bioinformatics to find regions of similarity between DNA sequences. Unlike global alignment (which you might know from Needleman-Wunsch), local alignment finds the best matching subsequences without forcing the entire sequences to align.

![Game Screenshot](https://media.giphy.com/media/Ln2dAW9oycjgmTpjX9/giphy.gif)  
*"When your sequences finally align perfectly"*

## 🚀 Features


- **Interactive matrix visualization** - Watch the scoring matrix fill up step-by-step
- **Guess Mode** - Test your understanding by predicting cell values
- **Auto-run** - Sit back and watch the algorithm work its magic
- **Traceback visualization** - See how the optimal path is found
- **Celebrations!** - Get confetti when you guess correctly
- **Customizable scoring** - Adjust match scores, mismatch penalties, and gap penalties
- **Works everywhere** - One HTML file works on phones and desktop directly in the browser


## 🎮 Demo 
*(**Click to play the game** )*
[Game Demo](https://alizayan684.github.io/Bioinformatics-Games/)  


## 🧪 How to Play

1. **Enter two DNA sequences** (or use the defaults)
2. **Set your scoring parameters** (match, mismatch, gap)
3. Click **"Initialize Matrix"** to start
4. Use:
   - **Next Step** to move through the algorithm
   - **Auto Run** to watch automatically
   - **Guess Mode** to test your skills
5. Watch the traceback to see the optimal alignment!

## 🧬 The Science Behind It

Local alignment uses the Smith-Waterman algorithm, which:
- It builds a scoring matrix where each cell represents the best alignment ending at that position
- Never allows negative scores (sets them to 0)
- Finds "islands" of positive scores representing similar regions
- The highest score identifies the best local alignment

![Science](https://media.giphy.com/media/3o6Zt6ML6BklcajjsA/giphy.gif)  
*"When you finally understand local alignment"*

**Happy aligning!** May your matches be plenty and your gaps be few. 🧬✨

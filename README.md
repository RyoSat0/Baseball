# Baseball 
"Baseball" is a classic 1v1 number-guessing game featuring a Tkinter-based GUI seamlessly integrated with Python game logic for an engaging player experience.

# Vision 
When I was in middle school, I often played this game with my friends during English class, which was not enjoyable and felt like it would last forever. It's a simple game that shouldn't be addictive, yet “just one more match” ends up consuming the entire class.

However, there’s one flaw with this game: sometimes, my friends are so silly that they incorrectly relay the outcomes of my guesses. Those who have played this game know that when this happens, winning becomes nearly impossible. This project aims to eliminate such mistakes. The program automatically provides the results for each guess, allowing players to focus on the game. So, go ahead, run the code, and try to become the next Shohei Ohtani!

<p align="center">
<img width="750" alt="Screenshot 2024-09-26 at 15 34 28" src="https://github.com/user-attachments/assets/bddb5704-dd2b-4096-b8bd-e274cdb47585">
</p>

## Game Rules
This game is a 1v1 number-guessing game that takes turns between players. 
Here's how it works:  
1. Both players select a secret 3-digit number where:
    - No digits repeat.
    - The number is composed only of digits 1 to 9 (no zeros allowed).
2. Players take turns guessing each other's secret numbers. Player A starts, followed by Player B.
3. After each guess, the game provides feedback:  
    - If a digit is correct but in the wrong position, it counts as a **ball**.  
    - If a digit is in the correct position, it counts as a **strike**.  
    - If none of the digits are in the secret number, it’s an **OUT**.  
4. The game continues until one player correctly guesses the opponent’s secret number.

## Example  
- **Secret number:** 168  
- **Guess 1:** 123 -> **Result:** 1 strike, 0 balls  
- **Guess 2:** 716 -> **Result:** 0 strikes, 2 balls  
- **Guess 3:** 824 -> **Result:** OUT  
- **Guess 4:** 168 -> **Result:** Player wins!

## License  
This project is licensed under the MIT License.

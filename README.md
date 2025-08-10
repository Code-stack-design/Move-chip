Reading inputs as a list:

We read a single line of input and convert it into integers using list(map(int, input().split())) — a concise and effective pattern for handling space-separated integers .

Parameter validation:

After reading the list, we compare its length to the expected n to catch mismatches and help the user correct any mistakes before processing.

Core logic (minCostToMoveChips):

Counts odd vs. even chip positions.

Since moves of ±2 are free, grouping by parity incurs zero cost.

Only crossing parities (±1 moves) cost 1 per chip—hence the minimum of odd/even counts is the answer.

#Screenshot

<img width="928" height="498" alt="image" src="https://github.com/user-attachments/assets/43ac08f4-51da-4578-9a9b-3793b1a0f179" />

#demo video

https://github.com/user-attachments/assets/2a81f0d5-7e01-4e2c-b8e3-6b1c27aa3de7

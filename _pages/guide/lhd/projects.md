---
layout: base
title: Project Ideas
description: Project Suggestions
---

Hackathons can be intimidating, especially as someone without much technical experience. That's 100% okay, because Local Hack Day is meant to serve as a supportive environment where you can take the time to learn something new! If you ever get stuck, seek help! There are mentors (and some peers) willing to lend a helping hand! Also feel free to ask questions on the #lhd-boulder channel on [Slack](localhackday.slack.com).

Here are some project ideas to start you off (for students who are taking/have taken CSCI 1300/2270, this is a great starting point)!

Note: These are merely guidelines/suggestions of how to go about making these projects. The features/details are entirely up to you. You might not necessarily finish the project within the day. As long as you learn something new, then it was worthwhile!

----

## Chess
- Start with making a 2-player mode.
- Make a board (8x8) to hold pieces.
- Pieces should be their own class (and have members such as current position, available moves, value. Here's a nice [Wikipedia page](https://en.wikipedia.org/wiki/Chess_piece_relative_value)) covering values.
- Have some way to see if either King piece is in check/checkmate
- Be able to take in user input from 2 different people, and change the board state
- Handle pawn promotion and castling
- Handle [En Passant](https://en.wikipedia.org/wiki/En_passant).
- Graphics? DevC++, SDL, SFML are good options.
- Possibly log game history, and be able to undo moves?
- AI (more difficult): Minimax algorithm with depth-limited search? Here's an [overview](https://medium.freecodecamp.org/simple-chess-ai-step-by-step-1d55a9266977).

----

## Minesweeper
- Different board sizes based on user-selected difficulty
- Random placement of mines
- Board should be able to hold mines and empty spaces
- Upon choosing an empty space, user should either: reveal more spaces if it wasn’t near a mine, or reveal a number if the square is near mines
- User should be able to flag squares (preventing square from being revealed until flag is taken off)
- Have a timer counting up (for score), for when user finishes the game (all non-mine squares are successfully revealed by user)
- If user selects a square with a mine, end game and reveal where all mines were
- Graphics? DevC++, SDL, SFML are good options.
- AI (more difficult): Here's a [starting point](https://luckytoilet.wordpress.com/2012/12/23/2125/).

----

## Planner
- Calendar that can hold events, classes, due dates, etc.
- User should have option to save (write to file) and load (read from file).
- New events should have names, descriptions, times (duration), dates, possibly repeating?
- Meetings/events with set durations could be specified within a time range, suggestions for possible times could be given as feedback
- Todo-list for the day, for the week?
- Different views? (daily, weekly, monthly?)
- Filter/group events (view only certain categories of events)
- Graphics? DevC++, SDL, SFML are good options.

----

## Calculator
- Evaluate different operations, given numerical inputs?
- As sophisticated as you want to make it (can it handle multiple lines of computations, or just simple addition?)
- Base converter? (Hexadecimal, binary, decimal)?
- Implement matrix operations?
- Quadratic formula solver?
- Perimeter/Area computation?
- Surface Area/Volume computation?

----

## Message Encryptor/Decryptor
- Implement different encryption algorithms given an input (either as user input or as a file), and output to a file
- Can start out with something easy (such as Caesar Cipher/Vigenere Cipher or Pig Latin), select different algorithms to apply to input before outputting?
- Read in file/user input and attempt to decrypt message.

----

## Monopoly
- Specifications, rules, etc. can be found [here](http://monopoly.wikia.com/wiki/Monopoly).
- Need random dice rolls
- Multiplayer support
- Graphics? DevC++, SDL, SFML are good options.
- This can pretty much be as complicated as you would like.

# Tic-Tac-Toe in Assembly Language

This project implements the classic Tic-Tac-Toe game using Assembly Language. It's designed to run on **emu8086**, an emulator for 16-bit x86 assembly programs.

## 📋 Project Overview

This is a two-player game where users take turns marking spaces on a 3x3 grid. The first player to align three of their marks horizontally, vertically, or diagonally wins. If all spaces are filled without a winner, the game ends in a draw.

## 🛠️ Features

- Two-player mode
- Text-based user interface
- Input validation to prevent overwriting existing marks
- Win condition detection (horizontal, vertical, diagonal)
- Draw detection when the board is full

## 🎮 How to Play

- Players take turns by entering a number from 1 to 9 corresponding to a cell on the grid.
- The board updates after every move.
- The game ends with a win message or a draw announcement based on the outcome.

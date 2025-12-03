# Arithmetic Practice

A web-based arithmetic practice application designed to help students master fundamental math operations through interactive problem-solving and comprehensive performance analytics.

## Overview

This application provides an engaging arithmetic practice environment that adapts to different skill levels and learning needs. Students can practice addition, subtraction, multiplication, and division with configurable difficulty levels, receive immediate feedback on their answers, and track their progress over time through persistent session analytics.

Key capabilities include:
- Multiple operation modes (addition, subtraction, multiplication, division, and mixed)
- Five difficulty levels per operation with age-appropriate problem ranges
- Vertical and horizontal problem display formats for varied practice
- Real-time performance metrics and accuracy tracking
- Division with remainder support (e.g., 17 ÷ 5 = 3R2)
- Comprehensive session history with LocalStorage persistence
- Post-session review of incorrect answers for targeted improvement

The application features a distraction-minimized interface with a blurred background, allowing students to maintain focus during practice sessions.

## Features

### Core Functionality
- **Multiple Operations**: Practice addition, subtraction, multiplication, division, or mixed operations
- **Adaptive Difficulty**: Five difficulty levels per operation, from single digits to multi-digit problems
- **Dual Display Modes**: Problems shown in both horizontal (e.g., 23 + 45) and vertical formats
- **Real-time Progress Tracking**: Live display of total problems, correct answers, wrong answers, and accuracy percentage
- **Session History**: Detailed statistics saved in browser LocalStorage with persistent data across sessions
- **Division with Remainders**: Proper handling of division problems with remainder notation (e.g., 4R3)

### Practice Modes
- **Addition**: From single digits to 3-digit numbers
- **Subtraction**: From single digits to 3-digit numbers with no negative results
- **Multiplication**: From times tables to 3-digit × 2-digit problems
- **Division**: From single-digit divisors to 2-digit ÷ 2-digit with remainder support
- **Mixed Operations**: Random combination of all four operations

### User Experience
- **Responsive Design**: Blurred background with centered practice interface for distraction-free learning
- **Wrong Answer Review**: End-of-session summary displaying all missed problems with correct answers
- **Visual Feedback**: Emoji indicators for correct (🐹) and incorrect (🐊) answers
- **Performance Analytics**: Session history with accuracy trends and total problems solved

## Getting Started

### How to Use

1. Select an operation type:
   - Addition (+)
   - Subtraction (−)
   - Multiplication (×)
   - Division (÷)
   - Mixed Operations
2. Choose difficulty level using the slider (5 levels available per operation)
3. Click "Start Practice" to begin your session
4. Type your answer and press Enter to submit
5. For division problems with remainders, use format: `4R3` (quotient R remainder)
6. Click "Stop" to end your session and review results

## Difficulty Levels

### Addition
- Single digit (e.g., 3 + 7)
- 2 digits (e.g., 23 + 45)
- 2 digits - simple (e.g., 34 + 12, no carrying)
- 3 digits (e.g., 234 + 567)
- Large numbers (e.g., 1234 + 567)

### Subtraction
- Single digit (e.g., 9 − 4)
- 2 digits (e.g., 45 − 23)
- 2 digits - simple (e.g., 48 − 12, no borrowing)
- 3 digits (e.g., 567 − 234)
- Large numbers (e.g., 1234 − 567)

### Multiplication
- Times tables up to 12 (e.g., 7 × 9)
- 1 digit × 2 digits (e.g., 7 × 23)
- 2 digits × 1 digit (e.g., 23 × 7)
- 2 digits × 2 digits (e.g., 23 × 45)
- Large numbers (e.g., 234 × 56)

### Division
- Single digit (e.g., 10 ÷ 3 = 3R1)
- Times tables up to 12 (e.g., 75 ÷ 9 = 8R3)
- 2 digits ÷ 1 digit (e.g., 85 ÷ 7 = 12R1)
- 3 digits ÷ 1 digit (e.g., 456 ÷ 8 = 57)
- 2 digits ÷ 2 digits (e.g., 97 ÷ 12 = 8R1)

### Mixed Operations
- Easy - 1 digit
- Medium - 2 digits
- Hard - 3 digits

## File Structure

- `index.html` - Main application
- `background.jpg` - Background image

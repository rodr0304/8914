# CST8914 - Lab 10: Accessible JavaScript

## Overview
This lab focuses on improving keyboard accessibility using JavaScript. The main objective is to implement the **roving tabindex technique**, allowing users to navigate a menu using only the keyboard.

## Features Implemented
- Keyboard navigation:
  - Arrow Down (↓) moves to the next menu item
  - Arrow Up (↑) moves to the previous menu item
- Enter key selects a menu item
- Escape key closes the menu
- Focus is managed programmatically using JavaScript
- Only one item is focusable at a time using:
  - `tabindex="0"` for the active item
  - `tabindex="-1"` for all other items

## Accessibility Improvements
- Implemented roving tabindex pattern
- Improved keyboard navigation for accessibility
- Updated `aria-expanded` to reflect menu state
- Added visible focus styles for better user experience

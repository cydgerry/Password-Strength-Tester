# Password-Strength-Tester
Constructing Password Strenght Tester. This will be an automated tool that will take in a user provided password, automatically assess it for quality and complexity, and give back an overall strength score.
# Password Strength Tester
**Developed by Mercydes Oliva**

## Overview
The Password Strength Tester evaluates a user-provided 
password across several security factors including length, complexity, 
common patterns, and known weak-password lists. The tool provides an objective 
score (0–100), a strength rating, and clear recommendations for improvement.

## Features
- Length evaluation with weighted scoring  
- Uppercase, lowercase, digit, and special-character detection  
- Sequential pattern detection  
- Repeated character detection  
- Weak-password dictionary matching  
- Returns score, rating, and recommendations  

## How It Works
The system evaluates the password using four core components:
1. **Length Score**
2. **Complexity Score**
3. **Pattern Detection**
4. **Dictionary Check**

The main function, `evaluate_password()`, aggregates results and normalizes the score.

## Technology Stack
- Python 3.x  
- Regular Expressions (`re` module)

## Usage
Clone the repo:

```bash
git clone <your_repo_here>
cd password-strength-tester

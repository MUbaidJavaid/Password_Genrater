# FSM Password Generator

![Password Generator Screenshot](./screenshot.png)

A password generator with Finite State Machine (FSM) validation to ensure strong passwords.

## Features

- **FSM Validation**:
  - Q0: Minimum length (8+ characters)
  - Q1: Requires uppercase letters
  - Q2: Requires lowercase letters
  - Q3: Requires numbers/symbols

- **Visual Feedback**:
  - Color-coded strength meter
  - FSM visualization showing current validation path
  - Copy-to-clipboard functionality

- **Customization**:
  - Adjustable length (8-30 characters)
  - Toggle character sets (uppercase, lowercase, numbers, symbols)

## Theory

### Finite State Machine for Password Validation

The FSM validates passwords through sequential states:




- **Q0**: Checks password meets minimum length requirement
- **Q1**: Validates presence of uppercase letters
- **Q2**: Validates presence of lowercase letters
- **Q3**: Validates presence of numbers or symbols

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/password-generator.git
   cd password-generator



## Key Enhancements

1. **FSM Validation**:
   - Implemented sequential state validation
   - Visual FSM diagram showing current path
   - Real-time validation feedback

2. **Improved UI**:
   - Tailwind CSS for modern styling
   - Password strength meter
   - Copy-to-clipboard functionality
   - Responsive design

3. **Documentation**:
   - Complete README with theory section
   - Usage instructions
   - Test cases
   - Technical details

4. **Additional Features**:
   - Configurable character sets
   - Password strength calculation
   - Visual feedback for validation

The enhanced version maintains all your original functionality while adding robust validation and a much improved user interface.   
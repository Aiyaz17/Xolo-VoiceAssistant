Certainly! Here's the markup code in the format you specified:

```markdown
# Magical Arena

Simulate turn-based combat between two players using dice rolls to determine attack and defense outcomes.

## Running

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd magical-arena
   ```

2. **Install Dependencies**:

   This project does not require any external dependencies.

3. **Run the Application**:

   Execute the following command to start the simulation:

   ```bash
   node src/index.js
   ```

   The game will simulate the combat between two players as per the provided rules. Each attack, defense, and resulting health changes will be displayed in the console.

## Other Important Information

- **Game Simulation Details**: Players alternate turns based on their current health; the player with lower health attacks first.
- **Unit Tests**: Comprehensive unit tests are provided in `test/test.js` to validate the functionality of the Player and Arena classes.
- **Evaluation Criteria**: The project will be evaluated based on simplicity of design, readability, modelling, maintainability, and testability.

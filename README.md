# Magical Arena

Simulate turn-based combat between two players using dice rolls to determine attack and defense outcomes.

## Running

1. **Unzip the file**:

   UnZip the provided zip file and cd into it. 

3. **Install Dependencies**:
   Execute the following command to install the dependencies:

  ```bash
   npm install
   ```

5. **Run the Application**:

   Execute the following command to start the simulation:

   ```bash
   node src/index.js
   ```

   The game will simulate the combat between two players as per the provided rules. Each attack, defense, and resulting health changes will be displayed in the console.

6. **Test the Application**:

   Execute the following command to test the application:

   ```bash
   npm test
   ```

## Other Important Information

- **Game Simulation Details**: Players alternate turns based on their current health; the player with lower health attacks first.
- **Unit Tests**: Comprehensive unit tests are provided in `test/test.js` to validate the functionality of the Player and Arena classes.
- **Change Players attribute default values**: If you want to, you can change Default values of attributes from index.js file.

# Livewire Poll Application

This project is part of my learning journey in Laravel and Livewire, following the "Master Laravel and PHP" course. The goal is to build a poll management system using Livewire for real-time interactivity.

## Project Overview
The Livewire Poll Application allows users to:
- Create polls with multiple options.
- View a list of available polls.
- Vote on poll options.
- Display real-time updates without page reloads.

## Features
1. **Poll Creation**
   - Add a title for the poll.
   - Dynamically add or remove poll options.
   - Store polls in the database.

2. **Poll Listing**
   - Display all polls with their respective options and votes.
   - Show the number of votes for each option.

3. **Voting System**
   - Allow users to vote for a poll option.
   - Update vote counts in real-time.

4. **Real-Time Updates**
   - Use Livewire components for seamless interactivity.
   - Emit events for communication between components.

## Prerequisites
- PHP ^8.1
- Laravel ^11.0
- Livewire ^3.5.18
- A database (MySQL)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/livewire-poll-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd livewire-poll-app
   ```

3. Install dependencies:
   ```bash
   composer install
   ```

4. Set up the environment file:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database credentials.

5. Run migrations:
   ```bash
   php artisan migrate
   ```

6. Serve the application:
   ```bash
   php artisan serve
   ```

## Project Structure
- **Livewire Components**:
  - `CreatePoll`: Handles poll creation.
  - `Polls`: Displays the list of polls and handles voting.
- **Models**:
  - `Poll`: Represents a poll.
  - `Option`: Represents options for a poll.
  - `Vote`: Tracks votes for each option.
- **Views**:
  - `livewire.create-poll`: Form for creating polls.
  - `livewire.polls`: List of polls with voting functionality.

## Usage
1. Open the application in your browser (e.g., `http://127.0.0.1:8000`).
2. Create a new poll by entering a title and adding options.
3. View the list of polls and vote for an option.
4. See the vote counts update in real-time.

## Key Learnings
- Building interactive applications with Livewire.
- Using Livewire events for communication between components.
- Managing real-time updates in Laravel applications.
- Implementing database relationships for complex data models.

## Troubleshooting
If you encounter issues, consider the following:
- Ensure all migrations have been run: `php artisan migrate`.
- Check the browser console for JavaScript errors.
- Verify that Livewire is properly installed and configured.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Mouhammad NDOUR
Happy coding!


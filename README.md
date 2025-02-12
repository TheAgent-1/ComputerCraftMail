# ComputerCraftMail

ComputerCraftMail is a Minecraft mod that allows players to send local emails within the game using the ComputerCraft mod. This project provides a simple and efficient way to communicate with other players in your Minecraft world.

## Features

- **Server and Client Scripts**: Easily set up your email system with dedicated server and client scripts.
- **Local Email System**: Send and receive messages between players in your Minecraft world.
- **User -Friendly Interface**: Simple commands to send and check emails.

## Installation

To install ComputerCraftMail, follow these steps:

1. Ensure you have the ComputerCraft mod installed in your Minecraft environment.
2. Use the following commands to download the server and client scripts directly from GitHub:

   For the server-side:
   ```lua
   wget https://raw.githubusercontent.com/YourUsername/ComputerCraftMail/main/mail_server.lua
   ```

   For the client-side:
   ```lua
   wget https://raw.githubusercontent.com/YourUsername/ComputerCraftMail/main/mail_client.lua
   ```

3. To run the scripts, simply type the following commands in your ComputerCraft computer:

   - For the server: `mail_server`
   - For the client: `mail_client`

4. Restart your Minecraft server to load the scripts.

### Changing the Domain

If you want to change the email domain (e.g., from `spectre.local` to something else), you will need to clone the repository and modify the code directly:

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/ComputerCraftMail.git
   ```

2. Open the `mail_client.lua` file and locate the line that defines the domain:
   ```lua
   return email:match("^(%w+)@spectre%.local$")
   ```
   Change `spectre.local` to your desired domain.

3. Save your changes and run the modified client script.

## Usage

Once installed, you can use the following features to interact with ComputerCraftMail:

### User Login

- When you run the client script, you will be prompted to enter your email in the format `username@spectre.local`. Ensure you enter a valid email format to proceed.

### Main Menu

After logging in, you will see the main menu with the following options:

1. **Send Mail**: 
   - Select this option to compose and send an email.
   - You will be prompted to enter the recipient's email and your message.
   - Ensure the recipient's email is in the correct format before sending.

2. **View Inbox**: 
   - Select this option to fetch and view your inbox.
   - You will see a list of received emails, including the sender and timestamp.
   - You can choose to delete an email by entering its corresponding number.

3. **Exit**: 
   - Select this option to exit the email client.

## Contributing

Contributions are welcome! If you would like to contribute to ComputerCraftMail, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or support, please reach out to [Your Name] at [Your Email Address].

## Acknowledgments

- Thanks to the ComputerCraft community for their support and inspiration.
- Special thanks to [any other contributors or resources you want to acknowledge].

```

Feel free to replace `YourUsername`, `Your Name`, and `Your Email Address` with your actual GitHub username, name, and email address. If you have any more changes or additional information to include, just let me know!

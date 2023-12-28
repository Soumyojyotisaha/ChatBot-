# ChatComponent

This is a React  component designed to facilitate chat interactions with the Vercel AI SDK. The component utilizes the `useChat` hook from the "ai/react" package to manage user input, handle submissions, and manage loading states. The chat history is displayed in a visually appealing manner, with messages alternately labeled as either "GPT-4" or "You" based on the sender's role.

# Try Here 
```bash
chat-bot-ochre.vercel.app
```
![image](https://github.com/Soumyojyotisaha/ChatBot-/blob/main/Screenshot%202023-12-28%20115409.png)

## Features

- **User-Friendly Interface:** The component provides an intuitive interface for users to interact with GPT-4, with a clear distinction between user and assistant messages.

- **Dynamic Message Formatting:** Messages are formatted for readability, with line breaks appropriately handled to ensure a clean and organized display.

- **Submit Functionality:** Users can easily submit their messages through a responsive form. The input is processed through the `handleSubmit` function.

## Installation

To integrate this ChatComponent into your React project, follow these steps:

1. Install the "ai/react" package:

    ```bash
    npm install 
    ```

2. Import the `ChatComponent` into your project:

    ```javascript
    import ChatComponent from './path/to/ChatComponent';
    ```

3. Use the `ChatComponent` within your React application:

    ```jsx
    function App() {
        return (
            <div>
                {/* Other components or content */}
                <ChatComponent />
            </div>
        );
    }
    ```

## Usage

1. Import the `ChatComponent` into your React component or page.

2. Place the `ChatComponent` within the desired section of your application.

3. Customize the appearance and behavior by modifying the component's styling and event handlers.

## Props

The `ChatComponent` does not currently accept any external props. All functionality is managed internally through the `useChat` hook.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own projects.

---

*Note: Make sure to replace the placeholder "path/to/ChatComponent" with the actual path to the `ChatComponent` file in your project.*

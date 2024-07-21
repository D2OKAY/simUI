# simpleUI
A Simple UI design for Chat interface for Ollama, built with Electron.

The idea came from wanting to create a siimple 'turn key' app that can be used for students (my niece). For details on the story you can check out my article [Ollama UI for Students (Part 2) - Not active yet](link). The UI allows customization of the colors to make it quite different from someone else. 

<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <td style="padding: 0; width: 50%;"><img src=".github/UI_image1.png" alt="Main Interface" style="width: 100%;"></td>
    <td style="padding: 0; width: 50%;"><img src=".github/UI_image2.png" alt="Settings Panel" style="width: 100%;"></td>
  </tr>
</table>

You are free to modify anything you like, this is intended only for my educational purpose and not intended for production. Just needed a quick simpueUI to connect to my local [Ollama](https://ollama.com/). and I would be updating this as I use it more as it is useful to me. 

I started with calling this "Ollama Chat" and that is what the base code will show. But theoretically it can be changed to anything really. 

# Future Tasks : 

I am planning to work on this as a base to further enhance the UI focused on simple use, few things that I've noted to work on:

* (Priority) name customization directly from UI 
* (Priority) output templating & size (could be reactive)
* (Memory) Option to change number of past conversations to remember (adds to the instructions)
* (UI enhancement) Increase the chat-box size when the Settings and Prompt menus are closed. 
* (UI enhancement) Able to customize backgrounds with personalized pictures and drawings
* (Functionality) Going to be looking into possible ways to add useful mods (educational games, interactive educational contents..) 
* (Functionality) Few basic chatbot templates (expert in different subjects, personalized chat, also looking into 'Lorax')
* (Functionality) Educational website searches (REPO of links that can be housed that are educational and free) 
* (Functionality) Enhancing more language capabilities

  But honestly this is not my full time job (wish it was..) but for now its what I am doing to further my studies.

  Happy exploring! 

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed [Node.js](https://nodejs.org/) (which comes with [npm](http://npmjs.com/))
* You have a Windows/Linux/Mac machine.

## Installing simpleUI

To install simpleUI, follow these steps:

1. Clone the repository
   ```
   git clone https://github.com/D2OKAY/simpleUI.git
   cd simpleUI/Code
   ```

2. Install the dependencies
   ```
   npm install
   ```

## Using simpleUI

To use simpleUI, follow these steps:

1. In terminal, run the application
   ```
   cd simpleUI/Code   # Make sure you are in correct directory
   npm start
   ```

## Building simplchatUI

To build an executable file for simpleUI, use the following command:

```
npm run build
```

This will create a distributable package in the `dist` directory.


## License

This project uses the following license: [MIT License](LICENSE)

# ezyExpres-cli
The ezyexpres is a Generate tools and helpers Express.js project lap js boilerplate quickly


## Project root Structure :



```
celexpress/
├── bin/
│   └── celexpress.js         # CLI entry point
├── commands/
│   ├── create.js             # Project scaffolding
│   ├── makeController.js
│   ├── makeModel.js
│   ├── makeRoute.js
│   └── makeMiddleware.js
├── templates/
│   ├── js/
│   │   ├── server.js
│   │   ├── controller.js
│   │   └── route.js
│   └── ts/
│       ├── server.ts
│       ├── controller.ts
│       └── route.ts
├── utils/
│   └── fileHelpers.js        # Folder/file creation helpers
├── config/
│   └── defaultConfig.json    # Default CLI settings
├── package.json
├── README.md
├── .gitignore


```



## TEACH STACK 
| Package       | Purpose                                               | Notes                                                                       |
| ------------- | ----------------------------------------------------- | --------------------------------------------------------------------------- |
| **inquirer**  | Interactive prompts in the terminal                   | Very popular and flexible; supports lists, checkboxes, confirmations, input |
| **prompts**   | Lightweight alternative to Inquirer                   | Faster and minimal                                                          |
| **commander** | Command parsing (`cex create`, `cex make:controller`) | Industry standard CLI framework; integrates well with Node                  |

└── LICENSE

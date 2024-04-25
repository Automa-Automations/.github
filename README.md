# Automa - Super Simple Automation
Automa is a project that focuses on making AI & AI automation available to the general public at a low-low cost of `10$` for the base hosted plan, or `0$` for self hosting all of our infrastructure.

Automa aims to make any social media automation possible by simply spending 5-10 minutes configuring something, and then having it working for you. This is a powerful method of growing social accounts for any purpose, be it advertising dropshipping general-growth or anything else!

Automa aims to expand its capabilities via open-source contributions, paid subscriptions / credit systems and more. This allows the developers looking to make valuable contributions to also get a cut of profits, and them starting up their own spin on this project.


# Table Of Contents
Automa will expand to grow to insane numbers & users over the short coming years, hence we are attempting to make documentation a ritual. The table of contents provides easy access to the entire readme and also quick attachements to other general / help resources.
- [The technology stack](#technology-stack)


# Technology stack
The technology stack provides a strict set of rules to ensure the development environment is as flexible as possible, the stack also takes into consideration ease of setup for developers, self hosting options, and post hosting options to ensure the following:
- Ease of use
- Cost efficiency
- Program execution speed
- Sanity
- Development setup / environment should be configurable with one single installation/setup command.

## The technologies
We will be using the following technologies with a super short explination of why. We will keep thist list up to date if changes are made to the stack, and is agreed upon by the top contributions, but yet still taking into priority the choices made by the main maintainers @AdonisCodes & @WilliamFerns1
  
  ### Python
  Python is a simple language. Making backend services super simple to setup, maintain & update. It is also a language that most developers are familiar with. Another driving factor can be that many open/close models like GPT & LLAMA are extremely accurate in these languages, allowing the development to be exponentially faster using AI powered tools like copilot.
  
  ### Swift & SwiftUI
  The premium feel that many apple devices provide ensures that the applications are also of higher quality, this is intrinsically an important driver, as this will force the development of the IOS app to be up to standard, ensuring speedy development, yet fast development, as the tools provided for working with these languages & the IOS stack outperforms most other IDEs.
  
  ### Typescript + ReactJS
  ReactJS is a powerful library used to make web based applications, all be it a simple interaction with web based technologies, it usually lacks components. It is powerful yet as we slowly expand using ChakraUI + Figma to compile our own design system via Figma (LINK HERE)
  
  ### Neovim + VsCode + Xcode
  Any other developers are allowed to use any other code editors, but these are preferred as they essentially cover the entire stack so to speak. Here are the Ups for these technologies.
  - Neovim would be the main driver for the backend / web development, as the support is on par with zed/vscode
  - VsCode will most likely just be used for debugging, as nvim-dap is known to have various bugs (Probably just a lack of understanding)
  - Xcode will be used to do the obvious `mobile application`
  
  More code editors will be added to as we expand / get developers to specifically work on the electron / android clients.
  
  ### AWS CDK
  AWS CDK is essential to this project, as it allows us to quickly build automagically scaling code. It also fits into the philosophy of `it works on every machine if you have cdk + aws cli installed`. This essentially provides us with super simple interfaces to debug code locally, and ultra powerful compute to run humungous tasks like AI video generation.

  ### ExpressJS
  Express is an effective way to build backend applications, this will work as the synchronization layer between all the clients, and also the cdk functions. An option is using cdk + api gateway + lambdas to quickly build an application, but that will cause micro differences and code fluff which we don't need (We don't want the client business logic interfering with the bulky / infrastructure level tasks)

  <-- MORE TO BE ADDED -->

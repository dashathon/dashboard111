# Dashathon

The strong and beautiful Dashboard to evaluate the experience of your Hackathon audience!
Note that this Repository is only for developmental purposes and not intended to be installed by actual users.

## Installation
<br/>

1. Install [node](https://nodejs.org/en/) on your computer.
2. Install the Angular Cli - [Reference](https://angular.io/cli)

    ```bash
    npm install -g @angular/cli
    ```

3. Install [git](https://github.com/git-guides/install-git)

4. Clone this repository to your computer! [Reference](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

    ```bash
    git clone https://github.com/PascalPet/Dashboard1-Hacktrack.git
    ```

5. Install the dependencies needed for the frontend

    5.1. Navigate to the folder dashboard-client in your bash

    5.2. Install the npm packages

    ```bash
    npm install 
    ```

6. Install the dependencies needed for the backend

    6.1 Navigate to the folder dashboard-server in your bash

    6.2 Install [python3](https://www.python.org/downloads/)

    6.3 Install the dependencies from the requirements.txt

    ```bash
    pip install -r requirements.txt
    ```

## Usage
<br/>

1. Starting the frontend

    1.1 Navigate into the folder dashboard-client

    1.2 Run the frontend

    ```bash
    ng serve
    ```

2. Starting the backend

    2.1 Navigate into the folder dashboard-server

    2.2 Run the Python script (Note here, that your python command may differ, mine is set to "py", yours may be "python" or "python3"

    ```bash
    py server.py
    ```

## Some Angular/Clarity Commands
<br/>

1. You can have the Angular Cli produce code for you!

    1.1 Generate a new Component (with the html, scss, ts and spec.ts files) in the bash directory you currently are

    ```bash
    ng generate [YOUR-NEW-COMPONENT]
    ```

    *This will also include the Component in the Modules file, so you most likely will not have to touch that file.*

2. Use the Clarity Design System for the UI!

    2.1 You can find all the Components provided by Clarity [here](https://clarity.design/angular-components/)

    2.2 If you want to use the Icons provided by Clarity, you will need to add them manually to the app.moudules.ts file (and Import them of course)!
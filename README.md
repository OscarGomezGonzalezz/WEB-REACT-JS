This repository includes the complete backend (folder `DeliverUS-Backend`) and the `owner` frontend (folder `DeliverUS-Frontend-Owner`).

## Environment Setup

### a) Windows

* Open a terminal and run the command `npm run install:all:win`.

### b) Linux/MacOS

* Open a terminal and run the command `npm run install:all:bash`.

## Execution

### Backend

* To **redo migrations and seeders**, open a terminal and run the command

    ```bash
    npm run migrate:backend
    ```

* To **run it**, open a terminal and run the command

    ```bash
    npm run start:backend
    ```

### Frontend

* To **run the `owner` frontend application**, open a new terminal and run the command

    ```bash
    npm run start:frontend:owner
    ```

## Debugging

* To **debug the backend**, ensure there is **NO** running instance, click on the `Run and Debug` button in the sidebar, select `Debug Backend` from the dropdown list, and click the *Play* button.

* To **debug the frontend**, ensure there **IS** a running instance of the frontend you want to debug, click on the `Run and Debug` button in the sidebar, select `Debug Frontend` from the dropdown list, and click the *Play* button.

## Testing

* To check the correct functioning of the backend, you can run the included set of tests. To do this, run the following command:

    ```bash
    npm run test:backend
    ```
**Warning: The tests cannot be modified.**

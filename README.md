# Task Master - Task Management System

## Project Overview

Task Master is a Task Management System built using the Frappe framework.

## Prerequisites

- [Frappe Bench](https://frappeframework.com/docs/user/en/bench/guide) installed
- [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/) for frontend assets management

## Setup Instructions

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Jyothish9988/Task-Master.git
    cd Task-Master
    ```

2. **Install Dependencies:**

    ```bash
    bench setup requirements
    ```

3. **Create a New Site:**

    ```bash
    bench new-site task_master
    ```

4. **Install Frappe App:**

    ```bash
    bench --site task_master install-app Task_Master
    ```

5. **Migrate the Database:**

    ```bash
    bench --site task_master migrate
    ```

6. **Start the Development Server:**

    ```bash
    bench start
    ```

    The application should now be accessible at [http://localhost:8000](http://localhost:8000).

## Additional Configuration

- **Custom Scripts:**
  - If there are custom scripts or hooks, provide details on how to set them up.

- **Environment Variables:**
  - If there are any environment variables or configuration files, document how to set them.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).



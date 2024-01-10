# internsctl

`internsctl` is a command-line tool designed for system information retrieval and user management tasks. It provides functionalities to fetch CPU information, memory details, manage users, and retrieve file information.

## Features

- Fetch CPU information using `cpu getinfo`.
- Retrieve memory details using `memory getinfo`.
- Create a new user with `user create <username>`.
- List all users or only sudo users with `user list [--sudo-only]`.
- Retrieve file information including size, permissions, owner, and last modified time.

## Installation

Simply download or clone this repository to your local machine:

```bash
git clone https://github.com/neerajsharma684/internsctl.git


## Ensure the script (internsctl.sh) has executable permissions:
- chmod +x internsctl

Usage
Run the tool using the following syntax:

./internsctl [options] <command>
Examples

1. Fetch CPU information:
        ./internsctl cpu getinfo
        ![Screenshot 2024-01-10 162634](https://github.com/neerajsharma684/internsctl/assets/49265172/1d1edfbf-ceb6-4fa1-a0b8-69b49162059d)

2. Create a new user:
        ./internsctl user create <username>

3. Retrieve memory information:
        ./internsctl memory getinfo
        ![Screenshot 2024-01-10 162743](https://github.com/neerajsharma684/internsctl/assets/49265172/f6ff7492-0e16-4f88-84ee-522dc581c024)

4. List all the available options:
        ./internsctl ls
        ![Screenshot 2024-01-10 162425](https://github.com/neerajsharma684/internsctl/assets/49265172/68d89961-0ade-4034-a143-324b83746b11)

4. For more details and available commands, refer to the help message:
        ./internsctl --help
        ![Screenshot 2024-01-10 162144](https://github.com/neerajsharma684/internsctl/assets/49265172/cc6e937a-ad69-41d8-8142-1c49f29022f3)

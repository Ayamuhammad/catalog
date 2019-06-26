# Item Catalog
An application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## How to run the project

1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html).

2. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).

3. Clone or download the Vagrant VM configuration file from [here](https://github.com/udacity/fullstack-nanodegree-vm).

4. Open the above directory and navigate to the `vagrant/` sub-directory.

5. Open terminal, and type

   ```bash
   vagrant up
   ```

6. After the above command succeeds, connect to the newly created VM:

   ```bash
   vagrant ssh
   ```

7. Type `cd /vagrant/` to navigate to the shared repository.

8. Download or clone this repository, and navigate to it.

9. Install or upgrade Flask:
    ```bash
    sudo python -m pip install --upgrade flask
    ```
10. Set up the database:
    ```bash
    python database_setup.py
    ```
11. Run this application:
    ```bash
    python project.py
    ```
12. Open `http://localhost:8000/` in your Web browser, and browse

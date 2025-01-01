# Badminton Court Reservation System

## How to jump start the project

1. Clone this repository
    ```bash
    $ git clone https://github.com/brianshih95/Badminton_Court_Reservation_System.git; cd Badminton_Court_Reservation_System
    ```
2. Install the required packages
    ```bash
    $ npm install
    ```
3. Create a `.env` file at the same level as the `src` folder
   ```bash
   $ echo "MONGODB_URI=mongodb://localhost:27017/Badminton_Court_Reservation_System" > .env
   ```
4. Run the project
    ```bash
    # Run the mongodb in docker
    $ docker run --name badmintomDB -d -p 27017:27017 mongo

    # Run the project
    $ npm run dev
    ```
    And you should be able to login at `http://localhost:3000/login`

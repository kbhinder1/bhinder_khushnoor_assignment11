
# kkbinder1_coding_assignment11

## Instructions to Run the Web Application Locally

This Dockerized web application displays an <h1> tag with the text "Codin 1" using Create React App.

### Things to keep in mind before proceeding to next steps

Make sure you have Docker installed on your system. You can download Docker from [here](https://www.docker.com/get-started).

### Build and Run

1. Clone this repository to your local PC:

    ```bash
   gh repo clone kbhinder/bhinder_khushnoor_assignment11
    ```

2. Change into the project directory:

    ```bash
    cd kbhinder_coding_assignment11
    ```

3. Build the Docker image:

    ```bash
    docker build -t kbhinder_coding_assignment11 .
    ```

4. Run the Docker container:

    ```bash
    docker run -p 7775:3000 --name kbhinder1_coding_assignment11 kbhinder1_coding_assignment11
    ```

### Access the Web Application

Open your web browser and go to [http://127.0.0.1:7775](http://127.0.0.1:7775). You should be able to see the "Codin 1 website".

### Stop the Container

To stop the running container, use the following command:

```bash
docker stop kbhinder1_coding_assignment11
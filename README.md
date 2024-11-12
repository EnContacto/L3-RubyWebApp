# L3-RubyWebApp
This is a web application developed in Ruby that shows the user the day of the week, the current date and the number of days left until next Christmas. 

## Description

This is a simple web application built with Ruby. 
- Displays the day of the week.
- Displays the current date.
- Calculates and displays the number of days left until next Christmas. 

The application is designed to run on port `4568` by default.

## Features:
- Displays a time-based greeting (morning, afternoon, or evening).
- Shows the number of days remaining until the end of the year.

## Prerequisites
To run this application, ensure that the following are installed on your system:
- **Ruby** (version 3.3.6 or later)
- **Sinatra** (web framework)
- **Rackup**
- **Webrick**
- **Bundler**

## How to Run the Application

### Running Locally
To run the application on your local machine:
1. Clone or download this repository to your computer.
   ```bash
   git clone https://github.com/EnContacto/L3-RubyWebApp.git
   cd L3-RubyWebApp
2. Open a terminal in the root directory of the project.
3. Installs the dependencies using Bundle
   ```bash
   bundle install 
4. Start app with:
   ```bash
   ruby app.rb
Open your web browser and visit `http://localhost:4568` to see the application at work.
 
### Running with Docker
You can also run this application using Docker for a containerized environment.
1. In the project’s root directory, open a terminal and run:
   ```bash
   docker build -t rubywebapp .

2. After the image is built, run the container using:
   ```bash
   docker run -p 4568:4568 rubywebapp
The application should now be accessible at `http://localhost:4568` in your web browser.

## Additional Information
This application uses the date and time of the local machine to calculate the days and display the missing date and days.

## Troubleshooting
 - Ensure Docker is installed and running correctly if using the Docker setup.
 - Make sure no other application is using port `4568` before running the server.

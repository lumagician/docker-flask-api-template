# website-update-checker

build the container

        docker build --tag flask-docker .

run the image adn map the ports accordingly

        docker run -d -p 8000:5000 flask-docker
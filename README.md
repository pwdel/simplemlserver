# Simple CherryPy ML Server

* Creating a Simple Machine Learning Server with CherryPy
* Blog post for this repo can be found [here](https://www.patdel.com/simple-ml-server/)

## Usage Instructions

1. Using Docker, from the command line, build the image with `./0_buildimageandtag` and run the container with `docker-compose up` from the directory that the docker-compose.yaml file exists.

2. Test to ensure the CherryPy server is running with `./curltest.sh`

3. Test an API call to send data to get a prediction with `./posttest.sh`

4. Look for the prediction within `./app/output/prediction_output.json`

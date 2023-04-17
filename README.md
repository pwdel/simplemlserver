# Simple CherryPy ML Server

* Creating a Simple Machine Learning Server with CherryPy

## Usage Instructions

1. Using Docker, from the command line, build the image with `./0_buildimageandtag` and run the container with `1_run`

2. Test to ensure the CherryPy server is running with `./curltest.sh`

3. Test an API call to send data to get a prediction with `./posttest.sh`

4. Look for the prediction within `./app/output/prediction_output.json`
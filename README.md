Cloudinary Flask sample project
===============================

A simple Flask application that performs image upload and generates on the transformations of the uploaded image.

## Installing and running

1. Install [Python](http://www.python.org/getit/)
1. Install [Cloudinary python egg](https://github.com/cloudinary/pycloudinary#setup)
1. Get [a cloudinary account](https://cloudinary.com/users/register/free)
1. Copy the `cloudinary configuration` environment variables from the [Management Console](https://cloudinary.com/console):
1. Add the cloudinary configuration to the app.py file as following:

		# Cloudinary Configuration:
		cloudinary.config(cloud_name='your cloudname', api_key='your api key',
		                  api_secret='your api secret')

1. Run the server:

        $ python app.py
1. Browse to http://127.0.0.1:5000/

Good luck!

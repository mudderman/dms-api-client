# DMS API Client

This is just a simple client to test the [dms-api](https://github.com/mudderman/dms-api)

Before using it, please make sure that the dms-api is running on localhost:8080.

To use it, just open the client.html in a web browser.

Choose a file to upload, this can be just an empty text file or what ever you choose.
Then press the "Import 10 documents" button to simulate 10 documents being uploaded and processed.

The status of the calls will update periodically, making use of the status endpoint of the API.

No real error handling is being implemented here, we will just log the error to the console.

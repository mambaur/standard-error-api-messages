# standard-error-api-messages

When an API request fails due to request errors or server errors, an error response message is returned in JSON format.

An error response message is returned in JSON format even for endpoints that support other MIME types. The error response message includes error message itself, a description of the error, a unique error code for the endpoint, an HTTP response message, and an HTTP response code.

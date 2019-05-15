# Appriss-PDMP-Integration

Launched from Epic's Hyperspace, this web application utilizes URL query parameters to retrieve the needed provider, location and patient information from Chronicles using the runQuery web service.  This data is then used to build the XML request to post to the Appriss web API.  The web application will process then response from Appriss and will either display the requested report or will redirect the user to a state PDMP website when a report cannot be returned.

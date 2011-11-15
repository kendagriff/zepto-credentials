# Zepto Plugin For Sending Cross Domain Authentication In AJAX

When using JavaScript and CORS across domains, browsers fail to send the request header with cookies, etc., to the server. This plugin adds `withCredentials` to the XHR settings using `beforeSend`.

IMPORTANT! Make sure your sever is configured for CORS, and includes:
    
    Access-Control-Allow-Credentials: true

## Usage

Just like so:

    <script type="text/javascript" src="zepto.credentials.js"></script>
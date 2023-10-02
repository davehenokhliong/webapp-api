I designed and developed a Web app that retrieves and displays ‘real-time’ passenger flight information from Hong Kong Airport Open Data. This REST web service provided by HK Airport returns historical data (including current calendar day) in JSON format. 

I displayed current calendar date departure and arrival passenger flight information, and the web app is nicely rendered on any desktop computer and smart phone.

Here is the specifications for the file:
- index.html for HTML code and the Javascript functions
- styles.css for responsive styles
- flight.php to allow our web server to act as a client to request flight data from Hong Kong Airport and relay the data to our web app, since unfortunately we cannot directly fetch HK Airport flight data through our web app (no CORS setting).
- iata.json for more descriptive information about an airport (since the destination and the origin airports are encoded by the standard IATA code, not full name of the airports)

Data provided by the REST API of the Airport Authority for building the Web App.
Website: https://data.gov.hk/en-data/dataset/aahk-team1-flight-info

Data dictionary about the request parameters and the response data set from here.
https://www.hongkongairport.com/iwov-resources/misc/opendata/Flight_Information_DataSpec_en.pdf

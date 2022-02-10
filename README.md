# Documentation for Bileto Implementation of OSDM API

Bileto implemented part of [OSDM](https://unioninternationalcheminsdefer.github.io/OSDM/) (Open Sales and Distribution Model) Specification to enable distributors with unified access to the Bileto Platform. This project documents supported workflows, and provides example to support developers.

## Content

* `examples/direct-reservation-booking`: Example JSON requests and responses for Direct Reservation Booking flow when the trip is pre-searched outside of OSDM.
  * `POST /trip-offers-collection`: [request diff 1.2 and 1.4](https://extendsclass.com/json-diff.html?url1=https://github.com/bileto/OSDM-API-Documentation/raw/master/examples/direct-reservation-booking/1.2-trip-offers-collection-request.json&url2=https://github.com/bileto/OSDM-API-Documentation/raw/master/examples/direct-reservation-booking/1.4-trip-offers-collection-request.json), [response diff 1.2 and 1.4](https://extendsclass.com/json-diff.html?url1=https://github.com/bileto/OSDM-API-Documentation/raw/master/examples/direct-reservation-booking/1.2-trip-offers-collection-response.json&url2=https://github.com/bileto/OSDM-API-Documentation/raw/master/examples/direct-reservation-booking/1.4-trip-offers-collection-response.json)

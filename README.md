# tiny-coding-exercise

Little task:

Create a docker-compose file and environment that can be spun up using `docker-compose up` which serves an API being able to return user information given a name.

## What does it require to do?

1. User wants to search for "Tina", and sends "Tina" to the API endpoint
2. The endpoint searches the users for a match
3. the system returns the following information:

- index
- name
- pac_id
- age
- diagnosis
- gender

The information can be returned in any format, json, text, list, ...

- The system should run with just `docker-compose up`
- fakepatients.csv should be imported, so e.g. "Tina" should return the third result in fakepatients
- fork this repo and submit your solution as a pull request

*Bonus points* if a new patient can be added


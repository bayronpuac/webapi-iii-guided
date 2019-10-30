# Middleware Notes

## Jargon 
Seperation of Concerns.

_we do NOT 

**EVERYTHING IS MIDDLEWARE!!**

Well, almost everything :-) 

## Types (based on how we got it ot who built it )

- built-in: included with express. ex: `express.json()`
- third party: must be installed from `npm`
- custom: we code these

## Types (based on how it's being used)

- global: runs on every request
- 
order matters, it goes top to bottom and left to right.

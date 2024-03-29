# Url Shortener Backend

## Goals to be accomplished
- Basic Authentication and url shortening feature (Done)
- Ability to give expiration time to shortened urls (Done)
- Forgot Password and Verify Mail (Required)
- Server side validations have to added (Required)
- Routes so that an authenticated user can see his shortened urls with original urls (Required)
- Ability to group certain shortened urls in a category (In Progress.....)
- Ability to delete selected shortened urls (Required)
- Ability to give heading and description for a shortened url (In Progress.....)
- Ability to monitor how many times a shortened url is used (Required)
- Code to be improved (Required)
- More modes of authentication can be added as required (Optional)
- Making it as much as featureful so that others can easily use it and create a frontend for it (Required)

## Project Overview 

### Routes

#### Register User
@Route - /api/auth/register
@Params - name (String), email (String), password (String)

#### Login User
@Route - /api/auth/login
@Params - email (String), password (String)

#### Shorten Url
@Route - /api/url/add
@Params - url (String), @optional expiration (Integer) [Epoch time in milliseconds] 
@Headers - Authorization :- Bearer {token}

#### This project is under MIT License.
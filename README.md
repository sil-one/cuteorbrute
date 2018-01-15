# Proposal for layout

Don't really know that much about angular/loopback yet. Just a proposal on general layout of pages/functionality from front-end perspective.

## login page

Contains the following parts:
- login, request    `POST /user/login`
- register, request `POST /user/register`

## user page

Contains the following parts:
- view user info `GET /user/{user_id}`
- modify user info `PUT /user`
- view posts made `GET /posts/user/{user_id}`
- create animal pic module `POST /pic`
- remove pic `DELETE /pic`

## ratings page

Perhaps this should be the default page after login.

Contains the following parts:
- view posts made by user `GET /posts/user/{user_id}`
- view based on rating `GET /posts/top`
- view based on location `GET /posts/location`
- view based on recommendation `GET /posts/recommendation`
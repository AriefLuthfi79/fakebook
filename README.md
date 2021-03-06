# [Fakebook](https://fm-fakebook.herokuapp.com/)

A social network clone built with Ruby on Rails. View it on [Heroku](https://fm-fakebook.herokuapp.com/).

Explore the app by logging in with one of the prepopulated accounts, or start from scratch with a blank guest account.

**Prepopulated account logins:**

```
email: jeanclaude@vandamne.com

password: kickboxer
```

```
email: chuck@norris.com

password: deltaforce
```

![friends](docs/friends.png?raw=true)

## Features

- Users must sign in to see anything except the sign in page.
- Users can send friend requests to other users.
- A user must accept the friend request to become friends.
- The friend request shows up in the notifications section of a user’s navbar.
- Users can create posts.
- Users can comment on posts.
- Users can like posts and comments.
- Posts are displayed in a timeline style, with all recent posts from the current user and his friends.
- Users can upload a profile picture and a cover picture.


## Technical Notes

- Postgresql database seeded with Faker gem.
- User sign-in uses the Devise gem.
- Posts, comments, and likes processed through AJAX request.
- Utilizes flash notices from native Rails and AJAX.
- Image attachments with CarrierWave gem, hosted on Amazon S3.
- Responsive layout
- SASS styling with Bootstrap components.

## Screenshots

### Sign-in page
![register](docs/register.png?raw=true)

### Timeline
![timeline](docs/timeline.png?raw=true)

### Post
![post](docs/post.png?raw=true)

### About page on smartphone
<p align="center">
  <img width="300" src="docs/about.png">
</p>

### Search page on smartphone
<p align="center">
  <img width="300" src="docs/index.png">
</p>


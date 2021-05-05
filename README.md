# Github-User-stats
simple github's user's stats fetch by pure html, css and js (web course project)

this app shows the user's profile pic, bio, Location, Name but you can add everything you want according to this JSON which github's api gives you:

{

  "login": "username",
  "id": 46835187,
  "node_id": "MDQ6VXNlcjQ2ODM1MTg3",
  "avatar_url": "https://avatars.githubusercontent.com/u/46835187?v=4",
  "gravatar_id": "",
  "url": "https://api.github.com/users/username",
  "html_url": "https://github.com/username",
  "followers_url": "https://api.github.com/users/username/followers",
  "following_url": "https://api.github.com/users/username/following{/other_user}",
  "gists_url": "https://api.github.com/users/username/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/username/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/username/subscriptions",
  "organizations_url": "https://api.github.com/users/username/orgs",
  "repos_url": "https://api.github.com/users/username/repos",
  "events_url": "https://api.github.com/users/username/events{/privacy}",
  "received_events_url": "https://api.github.com/users/username/received_events",
  "type": "User",
  "site_admin": false,
  "name": "firstName lastName",
  "company": null,
  "blog": "",
  "location": "Iran, Tehran",
  "email": null,
  "hireable": null,
  "bio": "CE student @ Amirkabir University of Technology",
  "twitter_username": null,
  "public_repos": 7,
  "public_gists": 0,
  "followers": 26,
  "following": 13,
  "created_at": "2019-01-19T05:18:21Z",
  "updated_at": "2021-03-25T14:53:41Z"
  
}

as you know the github's APIs are not free and they have some limitations on requests per minute so this app uses the local storage for
saving the previous requests.


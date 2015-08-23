# slackin-hunt

This is a fork from [slackin](https://github.com/rauchg/slackin)

Read more about the [motivations and history](http://rauchg.com/slackin) behind Slackin by G. Rauchg.


#### Deploy with Docker


Build the image

```
docker build -t slackin-hunt .
```

Run the image with your Slack team

```
docker run -p 3000:3000 -e SLACK_SUBDOMAIN="yoursubdomain" -e SLACK_API_TOKEN="yourapitoken" slackin-hunt
```

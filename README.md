# Slacker

### Description
Alpine image with a built-in script to post messages on slack


### Usage 

    docker run --rm -e SLACK_TOKEN radyum/slacker:latest send --channel <channel> --message <message> [ --icon <icon> ] [ --author <author> ]


* channel: Where you want to post your message
* message: The message you want to post
* icon: The profile picture shown alongside the author (eg: ```snowflake```)
* author: The author's name

## About

A nifty little tool by jxe to find people who follow interesting combinations of twitterers.

## Configuration

Create a twitter app and create a config.yaml file with the oauth info.

    consumer_key: ...
    consumer_secret: ...
    oauth_token: ...
    oauth_token_secret: ...


## Usage

Build a visual index of the people who follow both @bldgblog and @footage

    % ./twittermine mob bldgblog footage
    => Writing bldgblog-footage.mob.html
    
    % open bldgblog-footage.mob.html


Contact me with questions

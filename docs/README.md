# README

## Install

    brew install awscli hugo
    aws configure

## Setup Hugo

    hugo new site hermitic.org
    vim config.toml
    git clone https://github.com/Track3/hermit.git themes/hermit
    hugo new posts/my-first-post.md
    hugo new about/me.md
    hugo server -w -D
    aws s3 cp public s3://hermitic.org --recursive


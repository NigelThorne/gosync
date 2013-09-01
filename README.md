[![Build Status](https://secure.travis-ci.org/brettweavnet/gosync.png)](http://travis-ci.org/brettweavnet/gosync)

# gosync

Sync files, fast.

# Installation

Clone the repo:

    get clone https://github.com/brettweavnet/gosync

Chagne in the gosync directory and run make:

    cd gosync
    make

# Setup

Set environment variables:

    AWS_SECRET_ACCESS_KEY=yyy
    AWS_ACCESS_KEY_ID=xxx

# Usage

    gosync sync source target

## From local directory to S3

    gosync sync /files s3://bucket/files

## From S3 to local directory

    gosync sync s3://bucket/files /files

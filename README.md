#!/bin/sh
curl --user <jenkinslogin>:<API Token>  http://localhost:8082/job/MyJob/build?token= ausdj4537
echo "jenkins from an external script"
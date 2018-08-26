## Docker Fluentd Logger
When you are running application and need to use fluentd logger, sometimes it is cumbersome to configure and install and run in each system. While if you run on docker, no need to worry just copy and do the below commands.

<pre>
docker-compose up -d
</pre>

#Configuration

There is a configuration file for fluent.conf in the directory, you can change according to your need.

#Data

Data is stored in the /data directory. Once you start the docker and send log to fluentd, you will see files inside this directory.

#Remarks

If you liked the repo, don't forget to give me star. Happy Dockering !! :)

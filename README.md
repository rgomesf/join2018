# join2018
Introduction to Modern Graph Analysis using opensource tools like Tinkerpop and Janusgraph


## Steps
1. git clone https://github.com/rgomesf/join2018.git
2. docker build --rm -f Dockerfile -t join2018:latest .
3. docker run --rm --name=demo -d -p 80:80 -p 8182:8182 join2018
4. docker exec -it demo bash
5. /work/janusgraph/bin/gremlin.sh
6. :remote connect tinkerpop.server conf/remote.yaml session-managed
7. :remote console
8. Go to https://github.com/rgomesf/join2018/wiki/Exercises for the exercises  

### Exit
9. :q
10. exit
11. docker stop demo

**NOTE: Your run.sh encoding must be LR and not CRLF. Check the file after the pull**
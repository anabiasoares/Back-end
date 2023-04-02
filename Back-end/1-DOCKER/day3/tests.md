anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose up -d
[+] Running 11/11
 ⠿ database Pulled                                                                           37.1s
   ⠿ fb0b3276a519 Pull complete                                                               8.8s
   ⠿ c81bcd64a2d2 Pull complete                                                               8.9s
   ⠿ 45ed91f63dfa Pull complete                                                               9.1s
   ⠿ 06d1770a2c11 Pull complete                                                               9.5s
   ⠿ a03d917eab2f Pull complete                                                               9.6s
   ⠿ ae23fd926d52 Pull complete                                                               9.7s
   ⠿ 6e23a31f2628 Pull complete                                                               9.8s
   ⠿ 1f1670c0330a Pull complete                                                              35.1s
   ⠿ 37e00f823fe5 Pull complete                                                              35.3s
   ⠿ 0b9005a5f20f Pull complete                                                              35.5s
[+] Building 39.2s (9/9) FINISHED                                                                  
 => [day3_backend internal] load build definition from dockerfile                             0.1s
 => => transferring dockerfile: 111B                                                          0.0s
 => [day3_backend internal] load .dockerignore                                                0.1s
 => => transferring context: 2B                                                               0.0s
 => [day3_frontend internal] load build definition from dockerfile                            0.0s
 => => transferring dockerfile: 112B                                                          0.0s
 => [day3_frontend internal] load .dockerignore                                               0.1s
 => => transferring context: 2B                                                               0.0s
 => [day3_frontend internal] load metadata for docker.io/betrybe/docker-compose-example-fron  2.4s
 => [day3_backend internal] load metadata for docker.io/betrybe/docker-compose-example-backe  2.2s
 => [day3_backend 1/1] FROM docker.io/betrybe/docker-compose-example-backend:v1@sha256:8216  12.4s
 => => resolve docker.io/betrybe/docker-compose-example-backend:v1@sha256:821621f14a808f6b40  0.0s
 => => sha256:c20558be19214aa0543cdd547549fcd9e9eaf28a96b3aa798f6df7e41e8198 7.30kB / 7.30kB  0.0s
 => => sha256:6a428f9f83b0a29f1fdd2ccccca19a9bab805a925b8eddf432a5a3d3da04af 2.82MB / 2.82MB  5.8s
 => => sha256:c7ad74aede755227d79ac0411c549922ad260721212dcb2833a558798a24 36.37MB / 36.37MB  7.1s
 => => sha256:995c08d8ac36c3e26055c6a140c56fcc09741c9aadab8c226912fe3e6283a0 2.24MB / 2.24MB  3.9s
 => => sha256:821621f14a808f6b406272f3b162cecafd6d4c49d1937b55e9535f11f4f837 1.78kB / 1.78kB  0.0s
 => => sha256:eac3374fce0fd639864aafd04a3f4886cea683230faa360ae57f557232c0351d 282B / 282B    4.3s
 => => sha256:533540fcd02b5161d0b07f37d43fddbe62656bf946f1b5af9439bee36b333e5f 127B / 127B    5.1s
 => => sha256:15860710bdaa4b380735390aac2a3ac900ae9f8c906407d9604ee83ba9ea40 1.03kB / 1.03kB  5.8s
 => => sha256:ee734b9eb06e5dd007d810073e20f312707a0d2ee735003c4a83d48bd6857 5.46MB / 5.46MB  11.0s
 => => extracting sha256:6a428f9f83b0a29f1fdd2ccccca19a9bab805a925b8eddf432a5a3d3da04afbc     0.2s
 => => extracting sha256:c7ad74aede755227d79ac0411c549922ad260721212dcb2833a558798a24e032     2.6s
 => => extracting sha256:995c08d8ac36c3e26055c6a140c56fcc09741c9aadab8c226912fe3e6283a0fb     0.2s
 => => extracting sha256:eac3374fce0fd639864aafd04a3f4886cea683230faa360ae57f557232c0351d     0.0s
 => => extracting sha256:533540fcd02b5161d0b07f37d43fddbe62656bf946f1b5af9439bee36b333e5f     0.0s
 => => extracting sha256:15860710bdaa4b380735390aac2a3ac900ae9f8c906407d9604ee83ba9ea4049     0.0s
 => => extracting sha256:ee734b9eb06e5dd007d810073e20f312707a0d2ee735003c4a83d48bd6857dc6     0.7s
 => [day3_frontend 1/1] FROM docker.io/betrybe/docker-compose-example-frontend:v1@sha256:31  36.6s
 => => resolve docker.io/betrybe/docker-compose-example-frontend:v1@sha256:310a1201b58e2d998  0.0s
 => => sha256:310a1201b58e2d998599f9db42b935bc0b62f1d4228a031215a7d3cd1b3088 1.79kB / 1.79kB  0.0s
 => => sha256:c7ad74aede755227d79ac0411c549922ad260721212dcb2833a558798a24 36.37MB / 36.37MB  6.9s
 => => sha256:995c08d8ac36c3e26055c6a140c56fcc09741c9aadab8c226912fe3e6283a0 2.24MB / 2.24MB  3.7s
 => => sha256:e39545ddcf845bc40ec1d0017a7b71ff0d2aa3f19c1eb1beb35796ae31c7f9 7.75kB / 7.75kB  0.0s
 => => sha256:6a428f9f83b0a29f1fdd2ccccca19a9bab805a925b8eddf432a5a3d3da04af 2.82MB / 2.82MB  5.6s
 => => sha256:eac3374fce0fd639864aafd04a3f4886cea683230faa360ae57f557232c0351d 282B / 282B    4.1s
 => => extracting sha256:6a428f9f83b0a29f1fdd2ccccca19a9bab805a925b8eddf432a5a3d3da04afbc     0.2s
 => => sha256:351ab1f154cc9a5278a39ef9112f6e75310dafb50c1d4294305edf80c5d68ee7 129B / 129B    6.7s
 => => sha256:5e9318450aa0aa5cfc36d834bc4512707b43919b49286b4d6591cc7dee 174.17kB / 174.17kB  7.3s
 => => sha256:b864aa4c3a7bb7b4d1266663ce5529a941cb51f804bf26651a475b1c6c1 93.46MB / 93.46MB  23.4s
 => => extracting sha256:c7ad74aede755227d79ac0411c549922ad260721212dcb2833a558798a24e032     2.6s
 => => extracting sha256:995c08d8ac36c3e26055c6a140c56fcc09741c9aadab8c226912fe3e6283a0fb     0.2s
 => => extracting sha256:eac3374fce0fd639864aafd04a3f4886cea683230faa360ae57f557232c0351d     0.0s
 => => extracting sha256:351ab1f154cc9a5278a39ef9112f6e75310dafb50c1d4294305edf80c5d68ee7     0.0s
 => => extracting sha256:5e9318450aa0aa5cfc36d834bc4512707b43919b49286b4d6591cc7dee819c9c     0.0s
 => => extracting sha256:b864aa4c3a7bb7b4d1266663ce5529a941cb51f804bf26651a475b1c6c19a43e    10.8s
 => [day3_frontend] exporting to image                                                        0.0s
 => => exporting layers                                                                       0.0s
 => => writing image sha256:62805fb3541e3e1cbdefb2f797d790a8854aff1e254cf9b63c2a6e2e2fca1504  0.0s
 => => naming to docker.io/library/day3_backend                                               0.0s
 => => writing image sha256:f9dd4e50bc7ef952096fe7c7dbab5a82045b1a61cdf5c0a9cc35888d1aa96dc2  0.0s
 => => naming to docker.io/library/day3_frontend                                              0.0s

Use 'docker scan' to run Snyk tests against images to find vulnerabilities and learn how to fix them
[+] Running 4/4
 ⠿ Network day3_default       Created                                                         1.0s
 ⠿ Container day3-database-1  Started                                                         1.7s
 ⠿ Container day3-backend-1   Started                                                         2.7s
 ⠿ Container day3-frontend-1  Started                                                         4.0s
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose ps
NAME                COMMAND                  SERVICE             STATUS              PORTS
day3-backend-1      "npm start"              backend             running             0.0.0.0:3001->3001/tcp, :::3001->3001/tcp
day3-database-1     "docker-entrypoint.s…"   database            running             27017/tcp
day3-frontend-1     "npm start"              frontend            running             0.0.0.0:3000->3000/tcp, :::3000->3000/tcp
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose up -d --build
[+] Building 1.7s (9/9) FINISHED                                                                   
 => [day3_backend internal] load build definition from dockerfile                             0.0s
 => => transferring dockerfile: 111B                                                          0.0s
 => [day3_backend internal] load .dockerignore                                                0.0s
 => => transferring context: 2B                                                               0.0s
 => [day3_frontend internal] load build definition from dockerfile                            0.0s
 => => transferring dockerfile: 150B                                                          0.0s
 => [day3_frontend internal] load .dockerignore                                               0.0s
 => => transferring context: 2B                                                               0.0s
 => [day3_backend internal] load metadata for docker.io/betrybe/docker-compose-example-backe  1.6s
 => [day3_frontend internal] load metadata for docker.io/betrybe/docker-compose-example-fron  1.5s
 => CACHED [day3_frontend 1/1] FROM docker.io/betrybe/docker-compose-example-frontend:v1@sha  0.0s
 => [day3_backend] exporting to image                                                         0.0s
 => => exporting layers                                                                       0.0s
 => => writing image sha256:de62ab1d89f56284bddc7826c882898580533307646d2fbadf7c0eb6e0a1b804  0.0s
 => => naming to docker.io/library/day3_frontend                                              0.0s
 => => writing image sha256:62805fb3541e3e1cbdefb2f797d790a8854aff1e254cf9b63c2a6e2e2fca1504  0.0s
 => => naming to docker.io/library/day3_backend                                               0.0s
 => CACHED [day3_backend 1/1] FROM docker.io/betrybe/docker-compose-example-backend:v1@sha25  0.0s

Use 'docker scan' to run Snyk tests against images to find vulnerabilities and learn how to fix them
[+] Running 2/2
[+] Running 2/3y3-database-1  Recreated                                                       0.4s
[+] Running 2/3y3-database-1  Recreated                                                       0.4s
[+] Running 3/3y3-database-1  Recreated                                                       0.4s
[+] Running 2/3y3-database-1  Recreated                                                       0.4s
[+] Running 2/3y3-database-1  Starting                                                        1.1s
[+] Running 2/3y3-database-1  Starting                                                        1.2s
[+] Running 2/3y3-database-1  Starting                                                        1.3s
[+] Running 2/3y3-database-1  Starting                                                        1.4s
[+] Running 2/3y3-database-1  Starting                                                        1.5s
[+] Running 2/3y3-database-1  Starting                                                        1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 2/3y3-database-1  Started                                                         1.6s
[+] Running 3/3y3-database-1  Started                                                         1.6s
 ⠿ Container day3-database-1  Started                                                         1.6s
 ⠿ Container day3-backend-1   Started                                                         2.1s
 ⠿ Container day3-frontend-1  Started                                                         3.1s
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose down
[+] Running 4/4
 ⠿ Container day3-frontend-1  Removed                                                         0.0s
 ⠿ Container day3-backend-1   Removed                                                         0.3s
 ⠿ Container day3-database-1  Removed                                                         0.3s
 ⠿ Network day3_default       Removed                                                         0.3s
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$  docker-compose up -d backend
[+] Running 3/3
 ⠿ Network day3_default       Created                                                         0.1s
 ⠿ Container day3-database-1  Started                                                         0.8s
 ⠿ Container day3-backend-1   Started                                                         1.7s
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose logs backend
day3-backend-1  | 
day3-backend-1  | > back@1.0.0 start /opt/compose-example-back
day3-backend-1  | > node .
day3-backend-1  | 
day3-backend-1  | Rodando o aplicativo de back-end na porta 3001
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose logs --tail 5 database
day3-database-1  | {"t":{"$date":"2023-03-31T18:56:53.963+00:00"},"s":"I",  "c":"NETWORK",  "id":51800,   "ctx":"conn1","msg":"client metadata","attr":{"remote":"172.19.0.3:40668","client":"conn1","doc":{"driver":{"name":"nodejs","version":"4.1.3"},"os":{"type":"Linux","name":"linux","architecture":"x64","version":"5.19.0-38-generic"},"platform":"Node.js v14.18.1, LE (unified)|Node.js v14.18.1, LE (unified)"}}}
day3-database-1  | {"t":{"$date":"2023-03-31T18:56:53.977+00:00"},"s":"I",  "c":"NETWORK",  "id":22943,   "ctx":"listener","msg":"Connection accepted","attr":{"remote":"172.19.0.3:40670","connectionId":2,"connectionCount":2}}
day3-database-1  | {"t":{"$date":"2023-03-31T18:56:53.978+00:00"},"s":"I",  "c":"NETWORK",  "id":51800,   "ctx":"conn2","msg":"client metadata","attr":{"remote":"172.19.0.3:40670","client":"conn2","doc":{"driver":{"name":"nodejs","version":"4.1.3"},"os":{"type":"Linux","name":"linux","architecture":"x64","version":"5.19.0-38-generic"},"platform":"Node.js v14.18.1, LE (unified)|Node.js v14.18.1, LE (unified)"}}}
day3-database-1  | {"t":{"$date":"2023-03-31T18:56:53.996+00:00"},"s":"I",  "c":"NETWORK",  "id":22944,   "ctx":"conn1","msg":"Connection ended","attr":{"remote":"172.19.0.3:40668","connectionId":1,"connectionCount":1}}
day3-database-1  | {"t":{"$date":"2023-03-31T18:56:54.001+00:00"},"s":"I",  "c":"NETWORK",  "id":22944,   "ctx":"conn2","msg":"Connection ended","attr":{"remote":"172.19.0.3:40670","connectionId":2,"connectionCount":0}}
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ docker-compose down
[+] Running 3/3
 ⠿ Container day3-backend-1   Removed                                                         0.3s
 ⠿ Container day3-database-1  Removed                                                         0.2s
 ⠿ Network day3_default       Removed                                                         0.3s
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/1-DOCKER/day3$ 
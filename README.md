# snp-prototype-mongodb-client

A basic MongoDB instance that is used as a client and is bootstrapped with some scripts that can be viewed or executed.  

This is used to support the [Semantic Normalization Prototype](https://github.com/jlgrock/snp-prototype).  Documentation on how to use this can also be found there.

Development Procedures:
  - `sudo docker build -t jlgrock/snp-prototype-mongodb-client`

Release Procedures:
  - `sudo docker build -t jlgrock/snp-prototype-mongodb-client`
  - `sudo docker push jlgrock/snp-prototype-mongodb-client:[VERSION]` (replacing [VERSION] wit the actual version number)

Run Procedures:
  - see [Docker Hub](https://registry.hub.docker.com/u/jlgrock/snp-prototype-mongodb-client/)

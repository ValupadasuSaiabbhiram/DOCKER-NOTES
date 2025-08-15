# Delete docker image

1. List all Docker Images

> docker images

Example output:

> REPOSITORY                    TAG IMAGE ID                   CREATED                 SIZE> \
> ubuntu latest                     1d622ef86b13                    2 weeks ago             72.9MB> \
> nginx latest                        2bdc49f2f6a3                   3 weeks ago             142MB



2. Delete specific Docker Image

> docker rmi \<IMAGE\_ID>
>
> or
>
> docker rmi : \<REPOSITORY>:\<TAG>

3. Force Delete an image

> docker rmi -f \<IMAGE\_ID>


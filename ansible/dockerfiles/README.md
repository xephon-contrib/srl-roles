Launches an experiment master (i.e. emaster) container that lets the user orchestrate experiments. This experiment master is a container with Ansible and various parsers/graphing utilities.

This should be used as a tool in the [infra](https://github.com/systemslab/infra) experiment orchestration framework.

===================================================
Quickstart
===================================================

Launch the 
```bash
docker run --rm -it \
  --name="emaster" \
  -v `pwd`:/experiment \
  -v ~/.ssh:/root/.ssh \
  michaelsevilla/emaster
```

EOF

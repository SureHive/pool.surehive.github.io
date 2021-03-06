[Official release notes](https://github.com/input-output-hk/cardano-node/releases/)

## Upgrade Cardano-Node Version - 1.26.2 (latest)


### SSH to the relay/main node

```bash
ssh -i <location of the pem file> username@public_ip_adress
```

### clone git repository
```bash
git clone https://github.com/SureHive/pool.surehivegithub.io.git
chmod +x pool.surehivegithub.io/upgrade_cardano_node/*
```

### Run script upgrade_node_v1.2.6.2.sh in the background - script takes few hours :timer_clock: to complete
```bash
nohup ./pool.surehivegithub.io/upgrade_cardano_node/upgrade_node_v1.2.6.2.sh &
```
* `jobs` command will display status of the scripts that are running in the background 

* Display execution output of the `upgrade_node_v1.2.6.2.sh` script -  `tail -f nohup.out`

Congratulations! Your Cardano Node is upgraded to the latest version. :partying_face:

##### Note : Future upgrade scripts can be pulled by running `git pull` command.

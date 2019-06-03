# grid_htc_ce

A brief description of the role goes here.

Inspired by the [Puppet Module](https://github.com/cernops/puppet-htcondor_ce)
and the [Wiki entry](https://wiki.infn.it/progetti/htcondor-tf/htcondor-ce_setup).
There is also the [OSG documentation](https://bbockelm.github.io/docs/compute-element/htcondor-ce-overview).
## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should
be mentioned here. For instance, if the role uses the EC2 module, it may be a
good idea to mention in this section that the boto package is required.

## Role Variables

      grid_htc_ce_repo_install: true
      grid_htc_ce_repo_development_enable: false
      grid_htc_ce_batch_system: slurm
      grid_htc_ce_argus_server:


## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

## Example Playbook

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hephyvienna.htcondor-ce, x: 42 }

## License

MIT

## Author Information

Written by [Dietrich Liko](http://hephy.at/dliko) in June 2019

[Institute for High Energy Physics](http://www.hephy.at) of the
[Austrian Academy of Sciences](http://www.oeaw.ac.at)

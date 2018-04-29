Role Name
=========

Simple role to configure the /etc/bashrc

Requirements
------------

No reqs, only using template module.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Mandatory (not specified any way, have to be provided by the playbook or inventory or extra vars)
(none)

Optional (defaults)
```
bash_prompt_environment: 	String to show before  [user:hostname workdir]
bashrc_prompt_color:  		Set the color of the Bash Prompt. Use the tput value codes:
Color {code}	Color
0	Black
1	Red
2	Green
3	Yellow
4	Blue
5	Magenta
6	Cyan
7	White
```


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.


None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bashrc, bashrc_prompt_environment: "production", bashrc_prompt_color: 1 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

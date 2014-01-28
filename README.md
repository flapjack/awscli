awscli Cookbook
==============
Just takes care of installing the aws python command line utility.

Requirements
------------
Requires Python

e.g.
#### packages
- `python` - awscli needs the [python cookbook](http://community.opscode.com/cookbooks/python) and for python (and pip) to be installed

Usage
-----
#### awscli::default

Just include `awscli` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[awscli]"
  ]
}
```

Contributing
------------
Fork me on github, branch, submit a pull request. Or create an issue. Or talk on #flapjack on freenode. Or all of the above :-)

License and Authors
-------------------
Authors: Jesse Reynolds
License: MIT


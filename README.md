
# About the code

This command line script checks whether one of servers has access to other servers on internal network. It takes either a JSON file with servers and ports to check or a list of host/port combinations to make requests to. It makes HTTP requests concurrently so that one can get the status of servers as quickly as possible.

package is installed into our virtualenv in an editable way before testing the final product

```shell
pip install -e .
```
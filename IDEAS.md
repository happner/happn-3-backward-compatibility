- session needs to pass a disconnect instruction to the protocol plugin
- the layer service creates protocol stacks according to the configuration of the system
  - this means we have faster processing per request
  - we can leave out things like security and logging when these are not switched on
- the protocol success is in the stack, only the fail is out
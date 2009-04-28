# zend-progressbar

`Zend\ProgressBar` is a component to create and update progress bars in different
environments. It consists of a single backend, which outputs the progress through
one of the multiple adapters. On every update, it takes an absolute value and
optionally a status message, and then calls the adapter with some precalculated
values like percentage and estimated time left.


- File issues at https://github.com/zendframework/zend-progressbar/issues
- Documentation is at http://framework.zend.com/manual/current/en/index.html#zend-progressbar

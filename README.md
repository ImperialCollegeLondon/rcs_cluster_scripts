# RCS Cluster Scripts

A collection of handy scripts for use with the Imperial College Research
Computing Service cluster. To install, copy files somewhere in your PATH and
make sure they have execution permissions.

## Script list

* clear_logs
  * Delete job log (.o and .e) files from the current directory
  * Provide an argument to limit this to files with a given prefix
* latest_log
  * Open the most recent job log file in the current directory with `less`
  * Specify either o or e log files as the first argument
  * Provide a second argument to limit this to files with a given prefix
  * I usually create the below aliases
    * `alias llo="latest_log o"`
    * `alias lle="latest_log e"`
* qdel_last
  * Delete the most recently submitted job from the queue

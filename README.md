# NrvrCommander - Repository README

NrvrCommander is a Python package for devops and QA automation around
virtual machines, VMware, Enterprise Linux 6.x, and more.

If you got this from the source repository
(at [github](https://github.com/srguiwiz/nrvr-commander))
and just want to use it, run **./installlocally.py**.

For what is provided in the package, see **src/README.txt**.

Other than src/, files in dev/ are NOT going into the Python package.

Good example uses showing off utility are
**dev/examples/make-an-el-vm-001.py** (guest command line Enterprise Linux),
**dev/examples/make-an-ub-vm-002.py** (guest command line Ubuntu), and
**dev/examples/qa/selenium/make-testing-vms-001.py**
(guest GUI Linux running Selenium, although this example as implemented
uses VM snapshots hence needs VMware Workstation or Fusion, but
you could use most of its techniques without snapshots in VMware Player).

Even though at first made and maybe most useful with some brands Linux,
and a specific brand machine virtualization,
code here is useful for automation with other operating systems,
physical machines, etc.

Details for hosting on different operating systems are kept in docs/.

This project is about getting stuff done reproducibly.

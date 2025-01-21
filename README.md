> # DISCLAMER:
> **THIS PROJECT IS STILL IN IMPLEMENTATION PHASE, TO THE POINT THAT IT ISN'T USABLE AT ALL YET.**

---

# Virtuoso Run

Much like [nektos act](https://github.com/nektos/act) (which served as initial inspiration), 
This project aspires to enable users to run CI/CD actions locally. 

In contrast with act, Virtuoso uses **pre-existing environments**, with the sole
dependency of having SSH Access to them, be them VMs, containers or physical machines.
Especially for VMs, Virtuoso supports using pre-existing snapshots. This design choice
enables users to customize several runner aspects, such as hardware, specs, etc.

Additionally, It can work with GitHub, GitLab and Gitea workflows, making it more versatile.

One more advantage of Virtuoso is having an internal secrets database which can be passed to
workflows without the need for modifications.

Lastly, Virtuoso comes in two flavors, both available after installation:
- CLI Interface
- GUI Interface


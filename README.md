# Batch Connect - Franklin & Marshall College Amsterdam Modelling Suite

A Batch Connect app designed for Franklin and Marshall College OnDemand that launches AMS within a batch job.
This app is based heavily on the Batch Connect Matlab app from OSC:
[bc_osc_matlab app](https://github.com/OSC/bc_osc_matlab)

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [AMS]
- [Xfce Desktop] 4+

For VNC server support:

- [TurboVNC] 2.1+
- [websockify] 0.8.0+

For hardware rendering support:

- [X server]

**Optional** software:

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job

[AMS]: https://www.scm.com/amsterdam-modeling-suite/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[X server]: https://www.x.org/
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## Install

Enable app development on your OOD instance and then follow directions
in the OOD documentation:

https://osc.github.io/ood-documentation/latest/install-ihpc-apps.html

## License

* Documentation, website content, and logo is licensed under
  [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
* Code is licensed under MIT (see LICENSE.txt)
* AMS' logo is a trademark or registered trademark of SCM

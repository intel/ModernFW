# ModernFW Project
1. [What is ModernFW?](#1-what-is-modernfw)
   * [Objectives](#objectives)
	 + [High Level](#high-level)
     + [Architectures](#architectures)
	 + [Host OS](#host-os)
2. [Getting Started](#2-getting-started)
3. [Status](#3-status)
4. [Dependencies](#4-project-dependencies)
5. [Community](#5-community)
	* [Join us](#join-us)
6. [Security](#6-security)



# 1. What is ModernFW?
**This project is an experiment and should not be used with production workloads.**

ModernFW is an experimental approach to building a minimum viable platform firmware for machines such as cloud server platforms. Traditional PC firmware packages have evolved over time and have emphasized backwards compatibility and generality of purpose. We are seeking to reduce the overall footprint, increase efficiency, and to improve the security posture of the system by eliminating capabilities that are not needed to meet requirements for platforms that serve more vertically integrated purposes.  For example, one avenue for exploration is to move any functionality that can be accomplished in the context of the operating system out of the firmware.
ModernFW is based on TianoCore, and any learnings will be shared upstream to that community and others.

## Objectives
### High Level
* Modern, native 64-bit boot process
* Just enough firmware to boot and self-maintain
* Eliminate legacy device types
* Minimal emulated and virtual device support
* Defer work to the OS where possible
* Hand off to host kernel sooner
* Minimize number of firmware drivers
* Modular, customizable configuration
* Shared code trees between firmware and kernel/OS

### Architectures
* x86-64, with specific hardware platforms to be determined in the future.

### Host OS
* 64-bit Linux
* Ohter server OSs based on community support and contributions

# 2. Getting Started

# 3. Status
This project is just starting out. We have taken a recent snapshot of TianoCore, removed several components not required for optimized boot, and are filing pull requests on remaining components to drive our approach. In the coming weeks and months we will be taking more significant steps to pare down to a minimum viable code base.

# 4. Project dependencies
TBD

# 5. Community

We are working on building a global, diverse and collaborative community around the ModernFW project. Anyone who is interested in [contributing](CONTRIBUTING.md) to the project is welcome to participate.

We believe that contributing to a open source project like ModernFW covers a lot more than just sending code. Testing, documentation, pull request reviews, bug reports, feature requests, project improvement suggestions, etc, are all equal and welcome means of contribution. See the [CONTRIBUTING](CONTRIBUTING.md) document for more details.

License: [BSD-2-Clause-Patent](https://opensource.org/licenses/BSDplusPatent)

## Join us

Join the conversation on our [mailing list](https://lists.01.org/mailman/listinfo/modernfw).

# 6. Security

**Reporting a Potential Security Vulnerability**: If you have discovered
potential security vulnerability in this project, please send an e-mail to
secure@intel.com. For issues related to Intel Products, please visit
https://security-center.intel.com.

It is important to include the following details:
  - The projects and versions affected
  - Detailed description of the vulnerability
  - Information on known exploits

Vulnerability information is extremely sensitive. Please encrypt all security
vulnerability reports using our *PGP key*

A member of the Intel Product Security Team will review your e-mail and
contact you to to collaborate on resolving the issue. For more information on
how Intel works to resolve security issues, see: *Vulnerability Handling
Guidelines*

PGP Key: https://www.intel.com/content/www/us/en/security-center/pgp-public-key.html

Vulnerability Handling Guidelines: https://www.intel.com/content/www/us/en/security-center/vulnerability-handling-guidelines.html

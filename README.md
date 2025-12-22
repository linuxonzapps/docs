# Mainframe Software Hub for Linux: Documentation

The Mainframe Software Hub for Linux provides open source packages not
available in distribution repositories or community-provided packages
for easy consumption.

It caters to Linux on IBM Z customers' strong desire to experiment with
new open source technologies that haven't yet gained support in the
Linux distributions or project-level release plans of open source
communities they are a part of.

This project builds and provides open source packages in their native
form, including binary, RPM, DEB, or container images. The builds
provided for each project depend upon what makes sense for the project,
and what the developer providing the binaries can confidently test.

## Project Resources

 * [Mailing list](https://lists.openmainframeproject.org/g/mainframe-software-hub-discussion) (main channel for team communication)
 * [Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/mainframe-software-hub-for-linux) (online team meetings, events)

## Organization Structure

### Users

#### Downloading Software

Packages for each project are available by clicking on the repository
named for the software you wish to use, and clicking on Releases. This
will provide a history of versions released, with downloads provided in
various formats.

#### Submitting issues

Issues related to software you wish to download can be submitted
directly in the repository that contains the downloads.

Issues unrelated to a specific project, or requests for projects for the
team to consider maintaining, can be submitted in the
[tsc](https://github.com/linuxonzapps/tsc) (Technical Steering
Committee) repository. This is also where information about team
meetings and more can be found.

### Developers

If you're interested in adding your project, join [our mailing
list](https://lists.openmainframeproject.org/g/mainframe-software-hub-discussion)
and introduce yourself!

The core of this project is the
[zlinux-artifacts-builder](https://github.com/linuxonzapps/zlinux-artifacts-builder),
which anyone can use to build a project and related download artifacts
that can be added to this organization. This project has its own
documentation.

Each project that has build instructions and downloads made available is
maintained in a separate repository with the project name. Once you join
the project, the team will work with you to set up a repository for the
project you're working on.

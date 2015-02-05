OpenCV FaceRecognizer
=======================

First things first: this software package is based on the great work of Philipp Wagner [1]. However,
Norman Koester and I (Florian Lier) created this package in order to provide a more distributed
approach to OpenCV based face recognition (and detection) using current robotics middleware
implementations and standardized installation and roll-out routines. At the time of writing
RSB [2] and ROS [3] are supported.

This documentation is *minimalitic*, which means it provides basic information on how to train
a model and run this software stack. If you need detailed information about the _internals_
please consult [4][5].

[1] http://bytefish.de
[2] https://code.cor-lab.org/projects/rsb
[3] http://www.ros.org/
[4] http://bytefish.de/blog/videofacerec/
[5] http://www.bytefish.de/blog/fisherfaces/

Installation
-------------

Dependencies ROS (Indigo):
	sudo apt-get ros-indigo-desktop ros-indigo-people-msgs ros-indigo-usb-cam

Dependencies ROS (Groovy):
	sudo apt-get ros-groovy-desktop ros-groovy-people-msgs ros-groovy-usb-cam

Hint: You might save some disk space by installing ros-[indigo|groovy]-base. We haven't actually
checked if it contains all the required packages. If you are familiar with ROS you may install
missing packages manually.


Dependencies RSB:
    TODO


Usage Learning
---------------
TODO


Usage Recognition
-----
TODO


Replication
-------------
TODO


LICENSE
-------------
# Copyright (c) 2012. Philipp
# Wagner <bytefish[at]gmx[dot]de>
# Norman Koester <nkoester[at]techfak.uni-bielefeld.de>
# Florian Lier <flier[at]techfak.uni-bielefeld.de>
#
# Released to public domain under terms of the BSD Simplified license.
#
# Redistribution and use in source and binary forms, with or without
# modification, are permitted provided that the following conditions are met:
# * Redistributions of source code must retain the above copyright
#          notice, this list of conditions and the following disclaimer.
#        * Redistributions in binary form must reproduce the above copyright
#          notice, this list of conditions and the following disclaimer in the
#          documentation and/or other materials provided with the distribution.
#        * Neither the name of the organization nor the names of its contributors
#          may be used to endorse or promote products derived from this software
#          without specific prior written permission.
#
#    See <http://www.opensource.org/licenses/bsd-license>

# THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
# "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
# LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
# FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
# COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
# INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
# BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
# LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
# CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
# LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
# ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
# POSSIBILITY OF SUCH DAMAGE.
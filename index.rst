.. Copyright 2013-2021 Lawrence Livermore National Security, LLC and other
   Spack Project Developers. See the top-level COPYRIGHT file for details.

   SPDX-License-Identifier: (Apache-2.0 OR MIT)

.. _spack-101:

===================
Tutorial: Spack 101
===================

This is an introduction to Spack with lectures and live demos. It was
last presented as a virtual event at `PEARC 2022 <https://pearc.acm.org/pearc22/>`_
on July 11, 2022. There is a full day of material here, along with extra sections
beyond what was presented at PEARC.

You can use these materials to teach a course on Spack at your own site,
or you can just skip ahead and read the live demo scripts to see how
Spack is used in practice.

.. _slides:

.. rubric:: Slides

.. image:: tutorial/images/ecp21-tutorial-slide-preview.png
   :target: _static/slides/spack-pearc22-tutorial-slides.pdf
   :height: 72px
   :align: left
   :alt: Slide Preview

:download:`Download Slides <_static/slides/spack-pearc22-tutorial-slides.pdf>`.

**Full citation:** Todd Gamblin, Gregory Becker, Massimiliano Culpo, Adam J. Stewart,
Michael Kuhn, and Harmen Stoppels. Managing HPC Software Complexity with Spack.
PEARC 2022. Boston, MA, USA. July 11, 2022.

.. _live-demos:

.. rubric:: Live Demos

We provide scripts that take you step-by-step through basic Spack tasks.
They correspond to sections in the slides above. You can use one of the
following methods to run through the scripts:

  1. When we host the tutorial, we provision VM instances in `AWS
     <https://aws.amazon.com/>`_, so that users who are unfamiliar with
     Docker can simply log into a VPM to do the demo exercises.

  2. We also provide the `spack/tutorial <https://hub.docker.com/r/spack/tutorial>`_
     container image on Docker Hub that you can use to do the tutorial on your local
     machine. You can invoke ``docker run -it spack/tutorial`` to start using the
     container.

You should now be ready to run through our demo scripts:

  #. :ref:`basics-tutorial`
  #. :ref:`environments-tutorial`
  #. :ref:`configs-tutorial`
  #. :ref:`packaging-tutorial`
  #. :ref:`developer-workflows-tutorial`
  #. :ref:`binary-cache-tutorial`
  #. :ref:`stacks-tutorial`
  #. :ref:`spack-scripting-tutorial`

Other sections from past tutorials are also available, although they may
not be kept up-to-date as frequently:

  #. :ref:`modules-tutorial`
  #. :ref:`build-systems-tutorial`
  #. :ref:`advanced-packaging-tutorial`

Full contents:

.. toctree::
   :maxdepth: 2
   :caption: Links

   Main Spack Documentation <https://spack.readthedocs.io>

.. toctree::
   :maxdepth: 3
   :caption: Tutorial

   tutorial_basics
   tutorial_environments
   tutorial_configuration
   tutorial_packaging
   tutorial_developer_workflows
   tutorial_binary_cache
   tutorial_stacks
   tutorial_spack_scripting
   tutorial_modules
   tutorial_buildsystems
   tutorial_advanced_packaging

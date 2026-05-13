.. meta::
   :description: {short description here}
   :keywords: {comma-separated keywords here}
   :date-modified: {YYYY-MM-DD}

.. _{RST page ref string here}:

Tutorial: {verb phrase with specific features or models that will be used}
==========================================================================

{SEO-friendly intro paragraph, no more than 3 sentences total.} This topic guides you through {description of end-to-end process here} using the AWS Neuron SDK. When you have completed it, you will {description of customer outcome here}.

Overview
--------

{Describe exactly what the customer will achieve by following the tutorial, including information on when they will use the process in this doc and a high-level review of the steps in it. This helps them quickly assess the relevance of the quickstart to their own use case.}

{Optional, signals learning level}

Before you start
----------------

.. note::

   Optional section.

This tutorial assumes that you have experience in the following areas:

* {list required knowledge or experience, provide links to reading if appropriate}
* ...

Model details
-------------

..   Optional section. Use this for training/inference tutorials that work with a specific model.

This tutorial uses the {X} model with the following settings:

* {list any important settings or configurations}

**Limitations:**

* {ex: tested and validated batch size up-to 16}

**Model support updates:**

* {note any recent changes or improvements in model support when updating this tutorial}
* {ex: the model now supports a seq-len up to 32K vs max sequence length of 16K in the prior release}

Prerequisites
-------------

{What the customer must have available in terms of hardware, software, accounts/permissions, and knowledge/skills. Provide links where appropriate.}

* {Required packages/services/tools/hardware with the supported versions, if any}
* {Account and auth requirements, if any}
* {System requirements, if any}
* {Required knowledge/skills, if appropriate}

----

Prepare your environment
------------------------

..   Optional section, where you provide any initial preparation or configuration the customer must perform, such as setting up a virtual environment, configuring environment variables, downloading a dockerfile template, etc. Basically, anything the customer must have in place and configured before starting into the steps below. Link to supporting documentation if further details are needed.

.. code-block:: bash

   # Example setup command
   pip install package_name

Step 1: {scoped task starting with a verb}
------------------------------------------

In this step, you will {describe the outcome of the task described in this step}.

{The first discrete task in the end-to-end process covered by the tutorial. Use active voice ("You do X", not "X is done by you") as best you can. Provide code, shell commands, or screenshots, that will make the subtask clear or easy whenever possible — never make the customer guess as to the specifics of the action you're asking them to take.}

First, you ...

{Optionally, provide some way for the user to confirm they were successful in performing the task, such as code or shell output, or running some command that let's them confirm they did everything correctly as instructed.}

Step 2: {scoped task starting with a verb}
------------------------------------------

In this step, you will {describe the outcome of the task described in this step based on the work they did in the prior step}.

{The next discrete task in the process covered by the tutorial. Use active voice ("You do X", not "X is done by you") as best you can. Provide code, shell commands, or screenshots, that will make the subtask clear or easy whenever possible — never make the customer guess as to the specifics of the action you're asking them to take.}

You ...

{Optionally, provide some way for the user to confirm they were successful in performing the task, such as code or shell output, or running some command that let's them confirm they did everything correctly as instructed.}

.. **{More steps as needed, following the same pattern as above. Each step should be a discrete task that builds on the previous steps, leading to the final outcome of the tutorial.}**

Step N: {scoped task starting with a verb}
------------------------------------------

In the final step, you will {describe the outcome of the task described in this step based on the work they did in the prior step}.

{The last discrete task in the process covered by the tutorial. Use active voice ("You do X", not "X is done by you") as best you can. Provide code, shell commands, or screenshots, that will make the subtask clear or easy whenever possible — never make the customer guess as to the specifics of the action you're asking them to take.}

You ...

{Optionally, provide some way for the user to confirm they were successful in performing the subtask, such as code or shell output, or running some command that let's them confirm they did everything correctly as instructed.}

All complete! Now, let's confirm everything works.

Confirmation
------------

{Provide them with a way to know they've done everything correctly. This could be a screenshot, command-line output, a tool to launch, or specific settings to check.}

Congratulations! You have now {what the user has accomplished}. If you encountered any issues, see the **Common issues** section below.

----

Benchmarks
----------

.. note::

   Optional section. Include expected performance numbers by hardware platform.

.. list-table::
   :header-rows: 1

   * - Platform
     - Metric
     - Value
   * - {Trn2}
     - {OTPS / Throughput / Latency}
     - {value}
   * - {Trn3}
     - {OTPS / Throughput / Latency}
     - {value}

{ex: OTPS vs Overall throughput Pareto Curve (latency vs. throughput) and/or Table. BS stands for Batch-size. Include perf dashboard screenshots/images if you can.}

{Model owners should update this section for every release with the latest performance numbers from the Grafana dashboard.}

Common issues
-------------

Uh oh! Did you encounter an error or other issue while working through this tutorial? Here are some commonly encountered issues and how to address them.

- **{Problem 1}**: {Solution}
- **{Problem 2}**: {Solution}
- **{Problem 3}**: {Solution}

Clean up
--------

.. note::

   Optional section.

{Explain how to clean up any resources or environment changes used in this tutorial, if needed.}

Next steps
----------

Now that you've completed this tutorial, take your work and dive into other topics that build off of it.

* {link to topic that builds off this quickstart}
* {link to topic that builds off this quickstart}

Further reading
---------------

.. note::

   Optional section.

* {link with description here}
* {link with description here}

.. (Note to both the writer and any AI incorporating this template: The content below is provided as a resource and should not be included as-is in any final document created using this template as a basis.)

.. Diagram/images syntax:

.. image:: images/diagram-name.png
   :alt: {Alt text for diagram}
   :align: center

.. Code block syntax:

.. code-block:: python

   # Example Python code
   def example_function():
       pass

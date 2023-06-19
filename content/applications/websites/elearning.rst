:nosearch:

=========
eLearning
=========

With the **eLearning** app, you can easily upload content, define learning objectives, manage
attendees, assess students' progress, and even set up rewards. Engaging participants in a meaningful
learning experience enhances their attentiveness and fosters heightened productivity.

.. important::
   You can manage your **eLearning** content on both the **front end** and the **back end**. The
   **front end** allows you to create content quickly from your website, while the **back end**
   allows you to work directly from the app. It gives the same options as the front end but it
   also provides access to more advanced configurations and allows collaboration. This
   documentation presents the eLearning app from the back end.

You can enable different features to customize your courses by going to :menuselection:`eLearning
--> Configuration --> Settings`:

- **Certifications**: To evaluate the knowledge of your attendees and certify their skills;
- **Paid courses**: To sell access to your courses on your website and track revenues;
- **Mailing**: To update all your attendees at once through mass mailings;
- **Forum**: To create a community and let attendees answer each other's questions.

.. note::
   - Enabling :guilabel:`Certifications` installs :guilabel:`Surveys`;
   - Enabling :guilabel:`Paid courses` installs :guilabel:`Invoicing`;
   - Enabling :guilabel:`Mailing` installs :guilabel:`Email Marketing`;
   - Enabling :guilabel:`Forum` installs :guilabel:`Forum`.

.. seealso::
   - `eLearning app  <https://www.odoo.com/app/elearning>`_
   - `eLearning tutorials <https://www.odoo.com/slides/elearning-56>`_

Courses
=======

By going to :menuselection:`eLearning --> Courses --> Courses`, you can get an overview of all your
courses and a brief quantitative summary of each course.

Click on the :guilabel:`Course title` to edit your course back end. Click on :guilabel:`View Course`
to see your course front end.

Course creation
---------------

Click :guilabel:`New` to create a new course. When the page pops up you can add your
:guilabel:`Course Title` and one or more :guilabel:`Tags` to describe your course. You can add an
image to illustrate your course by clicking on the :guilabel:`Edit` option. Four tabs allow you to
edit your course further:
:ref:`Content <elearning/content>`, :ref:`Description <elearning/description>`,
:ref:`Options <elearning/options>`, :ref:`Karma <elearning/karma>`.

.. image:: elearning/elearning-course-creation.png
   :align: center
   :alt: Create your elearning course.

.. _elearning/content:

Content tab
~~~~~~~~~~~

This tab allows you to manage your course content. Click on :guilabel:`Add Section` to divide your
course into different sections. Click on :guilabel:`Add Content` to create
:ref:`content <elearning/create-content>`. Click on :guilabel:`Add Certification` to assess the
level of understanding of your attendees, certify their skills, and motivate them. **Certification**
is part of the :doc:`Surveys <../marketing/surveys/create>` app.

.. _elearning/description:

Description tab
~~~~~~~~~~~~~~~

You can add a short description or information related to your course in the :guilabel:`Description`
tab. It appears under your course title on your website.

.. image:: elearning/course-description.png
   :align: center
   :alt: Add a description to your course.

.. _elearning/options:

Options tab
~~~~~~~~~~~

In the :guilabel:`Options` tab, different configurations are available:
:ref:`Course <elearning/course>`,  :ref:`Communication <elearning/communication>`,
:ref:`Access rights <elearning/access-rights>`, :ref:`Display <elearning/display>`.

.. image:: elearning/options-tab.png
   :align: center
   :alt: Overview of the Options tab

.. _elearning/course:

Course
******

Set up a :guilabel:`Responsible` for your course, and select a :guilabel:`Website` if you want
your course to be restricted to this website only.

.. _elearning/communication:

Communication
*************

- :guilabel:`Allow Reviews`: tick the box to allow attendees to like and comment on your content and
  to submit reviews on your course;
- :guilabel:`Forum`: add a dedicated forum to your course (only possible if **Forum** is installed);
- :guilabel:`New Content Notification`: select an email template sent to your attendees when you
  upload new content. Click on the green arrow to have access to the email template editor;
- :guilabel:`Completion Notification`: select an email template sent to your attendees once they
  reach the end of your course. Click on the green arrow to have access to the email template
  editor;

.. _elearning/access-rights:

Access rights
*************

- :guilabel:`Show course to`: define who can access your course and their content between
  :guilabel:`Everyone`, :guilabel:`Signed In` or :guilabel:`Course Attendees`;
- :guilabel:`Enroll Policy`: define how people enroll to your course. Select:

   - :guilabel:`Open`: if you want your course to be available to anyone;
   - :guilabel:`On Invitation`: if only people who received an invitation can enroll to your course.
     If selected, fill in the :guilabel:`Enroll message` explaining the enroll process to subscribe
     to the course. This message appears on your website under the course title;
   - :guilabel:`On Payment`: if only people who bought your course can attend it. The
     :guilabel:`Paid Courses` features must be enabled by going to :menuselection:`eLearning -->
     Configuration --> Settings` to get this option. If you select :guilabel:`On Payment`, you must
     add a :guilabel:`Product` for your course. Select an existing one or create a new one. It can
     be updated by clicking on the green arrow that redirects you to the :doc:`../sales/sales` app
     to finalize the configuration.

.. _elearning/display:

Display
*******

- :guilabel:`Training`: the course content appears as a training program, and the courses must be
  taken in the proposed order.
- :guilabel:`Documentation`: the content is available in any order. If you chose this option, you
  can select the :guilabel:`Featured Content` on the course homepage.

.. _elearning/karma:

Karma tab
~~~~~~~~~

This tab is about gamification to make e-learning fun and interactive.

In the :guilabel:`Rewards` section, set up the rewards you want to grant your students when they
:guilabel:`Review` or :guilabel:`Finish` a course.

In the :guilabel:`Access Rights` section, define the karma needed to :guilabel:`Add Review`,
:guilabel:`Add Comment`, or :guilabel:`Vote` for the course.

.. note::
   From your course, use the smart button :guilabel:`Contact attendees` to reach people who are
   already part of the course.

.. _elearning/create-content:

Course groups
-------------

Use the **Course Groups** to inform users and allow them to filter the courses from the
:guilabel:`All Courses` dashboard.

You can manage them by going to :menuselection:`Configuration -->
Course Groups`. Click :guilabel:`New` to create a new course group. Add the :guilabel:`Course Group
Name`, tick the :guilabel:`Menu Entry` box to allow users to search by course group on the website,
and add tags in the :guilabel:`Tag Name` column. For each tag, you can select a corresponding color.

.. _elearning/tags:

Content
=======

Manage your content by going to :menuselection:`eLearning --> Courses --> Contents`. Click
:guilabel:`New` to create content. Add your :guilabel:`Content Title`, and if you want
:ref:`Tags <elearning/tags>`, then fill in the related information among the different tabs.

.. image:: elearning/elearning-content-tab.png
   :align: center
   :alt: Create your content.

Document tab
------------

- :guilabel:`Course`: select the course your content belongs to;
- :guilabel:`Content Type`: select the type of your content;
- :guilabel:`Responsible`: add a responsible person for your content;
- :guilabel:`Duration`: indicate the time required to complete the course;
- :guilabel:`Allow Download`: allow users to download the content of the slide. This option is only
  visible when the content is a document;
- :guilabel:`Allow Preview`: the course is accessible by anyone, users don’t need to join the
  channel to access the content of the course;
- :guilabel:`# of Public Views`: it represents the views of the non-attending participants;
- :guilabel:`# Total Views`: it represents the total of the public views and the attendees' views.

Description tab
---------------

You can add a description of your content that appears front end in the :guilabel:`About` section of
your course content.

Additional resources tab
------------------------

Click :guilabel:`Add a line` to add a link or a file that supports your participants' learning.
It appears in the course content on your website.

.. image:: elearning/additional-content.png
  :align: center
  :alt: Additional ressources

Quiz tab
--------

From this tab you can create a quiz to assess your students at the end of the course.

:guilabel:`Points Rewards` can be filled in. They are offered to the participant based on the number
of trials to answer the question, and keep them engaged correctly. Then, create your
:guilabel:`Questions` and :guilabel:`Answers` by clicking on :guilabel:`Add a line`. A new window
pops up, and you can fill in the :guilabel:`Question Name` and add multiple answers by clicking on
:guilabel:`Add a line`. Tick the box for the correct answer. You can also fill in the
:guilabel:`Comment` field to display additional information when the answer is checked.

Content Tags
------------

The **Content Tags** help users to classify the content from the :guilabel:`Contents` dashboard.

You can manage them by going to :menuselection:`eLearning --> Configuration --> Content Tags`. Click
:guilabel:`New` to create a new tag.

Publish your content
====================

Everything created on the back end needs to be published from the front end. Unpublished content is
always visible from your website but still needs to be published to be available to your audience.

You must be on your website's front end to publish your content. To do so, click on the
:guilabel:`Go To Website` smart button, and tick the :guilabel:`Publish` option available in the
right-hand corner.

.. image:: elearning/elearning-publish-button.png
  :align: center
  :alt: Publish your content.

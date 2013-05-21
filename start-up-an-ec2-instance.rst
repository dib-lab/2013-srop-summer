Start up an EC2 instance
========================

Go to 'https://titus-courses.signin.aws.amazon.com' in a Web browser.

Select 'My Account/Console' menu option 'AWS Management Console."

Log in with username 'srop-student' and the password that the instructors
give you.

Click on EC2 (upper left).

Select "Launch Instance" (midway down the page), and select "Quick
Launch Wizard".

The launch wizard
~~~~~~~~~~~~~~~~~

.. image:: images/ec2-wizard.png
   :width: 90%

On this page,

1. Name your new computer something (here, "Adam"; name it after yourself instead).

2. Create a new key pair (here, "Adam"; name it after yourself instead) and Download it.

3. Select "More Amazon machine images."

4. Click on "Continue."  This will be greyed out until you download the
   key pair (button, upper right).

**Note:** You only need to create a new key pair the first time you're
doing this -- you can select the one you created the first time, if you
still have a copy of the key file you downloaded stored somewhere.

"Create a new instance" page 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Enter 'ami-999d49f0' into the search box and click "search".  You should
see "starcluster-base-ubuntu-".  Select it, and hit Continue.

"Create a new instance" page 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

On this page, "Edit details" until it looks like the below image --

.. image:: images/ec2-details.png
   :width: 90%

1. Make sure your "Type" is m1.large.

2. Make sure your "Availability zone" is something specific, like us-east-1c.

3. Make sure your "Security group" is set to default.

Then, click "Launch".

Wait for your instance to be running
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Go to the 'instances' list and make sure your particular instance is
running.

.. image:: images/ec2-instance-running.png
   :width: 90%

Then, go to :doc:`log-in-with-ssh-win`.

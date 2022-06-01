# 31 May 2022

## Mac terminal shortcuts
To copy the content in the terminal to clipboard

	$  pbcopy

To paste the content from clipboard to terminal.

	$ pbpaste

We can copy any output that returned by any process to the terminal to the clipboard we can simply use pipe.

	$ pwd
	/Users/<user name>

To copy the following output to the clipboard we can run

 	$ pwd | pbcopy
	/Users/<user name>


## Commiting the code
Before each commit we should ensure that it has a bussiness value like what behaviour we have acheived.

## Check equality
Last time when we are solving the poblem to find the lenggth of a given line segment, we have checked the equality for point class by veryfying that it is reflexive, symmetric, transitive, consistent because there will be only one point that has coordinates (0, 0) and in the problem where we have to find the perimeter of a given rectangle, there are many possibiles for rectangle with length 5 and breadth 6 in a cartesian system.  So here checking equality is meaningless.

## Attributes in Ruby

### attr_reader
It is used when when we have an attribute that has only read actions.

### attr_writer
It is used when when we have an attribute that has only write actions.

### attr and attr_accessor
They both mean the same context and they are used when we have an attribute that has both read and  write actions.


## Principles

### Self suffiicient
When we know the work that we should do, then do it before anyone says or waiting for anyone's help.

### Truck factor
(definition) The number of people on your team who have to be hit with a truck before the project is in serious trouble


## Assumptions
When we are working on a small problem there may not be any issue if go blind with our assumptios. But in large scale projects there may be many other thing that we don't know, In that case our code may fail. So we couldn't go through our assumptions.

## User Requirements
Before beginning to write the code we must gather user requirements regarding the project. There are good actors and bad actors. If we write the code for both good and bad actors, But user knows that there wiil be only good actors. Then it is waste of time to write the code for bad actors. So, It is best if know the user requirements before working on the project.


## End
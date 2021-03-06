# Gribot

Gribot is an **open source agricultural robot mower** that can cut grass in crops such as trees, grapes, etc. All software, modules, plans, models, with the exception of purchased elements, are freely available under LGPL.
Gribot is not only limited to agriculture: it can be used in every area where grass has to be periodically cut, such as 
roadsides, industrial areas, etc.

We are developping more that just a mower: we are creating a platform that can carry many tools: in a first step, we do focus on grass cutting.

# Project web site

The project web site is www.gribot.org.

# How to support us

there are several way to support our project.
* To participate, you can register via github of via <a href="https://gribot.org/i-would-like-to-participate/">Gribot</a> web site.
* You can fund our project in <a href="https://www.patreon.com/bePatron?u=11801662" data-patreon-widget-type="become-patron-button">becoming a Patron!</a>

In any case, do not hesitate to <a href="https://gribot.org/contact-us/">contact us</a> for any question or comment.

# Why gribot ?

Maintenance of grass in agricultural crops such as vines or fruit trees, road and motorway borders,
industrial zones, etc. Is mainly done with mowers, brush cutters, tractors and weed killers. Not only
are these operations time-consuming and costly, but they also generate a lot of CO2 and use pollutants.
That's why we want to automate these operations with an intelligent robot that can cut grass as close
to crops, trees, walls, etc. as possible, using GPS location, among other things, to avoid installing a
wire of delimitation.

We want to accelerate the transition to sustainable development, which is why we distribute all the
plans and software of our robot under GNU General Public License (GPL), except for ready-made
items such as motors, GPS modules, LIDAR , etc. Which are under the manufacturer's license.

# Project status

At the time being, it is possible to start playing with the simulator based on gazebo. It gives an idea of the eay Gribot should behave.

The master branch contains a working system. All development are made in dev branch (or other if necessary), and are merged into master only when they have been tested.

# Getting started 

Gribot is based on ROS Lunar. At the present time, it does not work with ROS Melodic as some packages used by gribot have not yet been ported ( eg. ros_canopen).

To use Gribot software, you have to do the following:

1. Install a Ubuntu 16.04 server if not already done
2. Install ROS Lunar packages
3. Create a catking working folder
4. Clone gribot git folder

If everything went well, you should be able to start gribot in typing the following command:

```
roslaunch gribot gribot.launch
```

# Contribution

Thank you to all the people who already contributed to Gribot.

<a href="https://github.com/guycorbaz/gribot/graphs/contributors">Contributors</a>

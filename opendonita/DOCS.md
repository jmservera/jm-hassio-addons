# Open Doñita Add-on

## How to use

This add-on integrates the Open Doñita server in your Home Assistant instance. It allows you to control your Conga 1390/1490/1590 robotic vacuum cleaners from Home Assistant.

Follow the [Open Doñita documentation](https://gitlab.com/rastersoft/opendonita/-/blob/master/README.md#connecting-the-robot-to-the-new-server) to configure your robot to use the Open Doñita server.

## Configuration

The Open Doñita server needs to **use ports 80 and 20008**, you don't need to forward them from your router because they will be used by the conga from your local network, but you need to ensure that there are no other services using those ports in your Home Assistant instance.

You will need to pair your Conga with your server, follow the instructions 
found on the [Open Doñita server site](https://gitlab.com/rastersoft/opendonita).
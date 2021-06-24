A rudimentary bitcoin node, written in PHP.

It's not actually a "node" because it doesn't relay any messages.

It basically just shows you how to connect to a node on the bitcoin network and start receiving messages from them, so you can see how the "handshake" works and what the data looks like that gets sent between bitcoin nodes.

## Usage

Go in to the folder and run:

`php node.php`

## Tips

* The only stuff you really need is four `socket_*` functions, and with those you can connect and send messages to bitcoin nodes. The rest of the script is just getting the right data in the right format (so that nodes can understand your messages correctly).
* Don't rely on this for anything. It's just a quick script to show you how easy it is to use PHP to connect to the bitcoin network. 

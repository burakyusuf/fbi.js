# fbi.js


const Discord = require("discord.js");

exports.run = async (client, message, args) => {
 
 const motion = new Discord.MessageEmbed()

.setColor("RED")
.setImage("https://media1.giphy.com/media/QUY2pzDAKVpX3QacCg/200.gif")
.setTitle("FBİ!");

  message.channel.send(motion);
}; 

exports.conf = {
  enabled: true,
  guildOnly: false,
  aliases: ["fbi-gif"],
  permLevel: `Yetki gerekmiyor.`
};

exports.help = {
  name: "fbi",
  description: "FBi gif atar",
  usage: "a!fbi"
};

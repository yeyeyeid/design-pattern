业务场景：发送消息
消息类型：普通消息、加急消息、特急消息
发送方式：短信、邮件、微信

根据bridge模式：
业务的变化具有两个维度，一个维度是抽象的消息，包括普通消息、加急消息和特急消息，这几个抽象的消息本身就具有一定的关系，加急消息和特急消息会拓展普通消息；另一个维度是在具体的消息发送方式上，包括系统内短消息、邮件短消息和手机短消息，这几个方式是平等的，可被切换的方式。

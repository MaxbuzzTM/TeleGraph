# TeleGraph
TeleGraph is a Telegram bot manager that support Plugins, each plugin can do everything with telegram.

```csharp
public void OnReviceMessage(Message message)
{
    pluginadaptor.OnMessage(this, "From: " + message.From.FirstName +"Message: " + message.Text + Environment.NewLine);    
}
```
TeleGraph

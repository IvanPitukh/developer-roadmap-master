# Multiple Scaling Triggers

> Don't use multiple scaling triggers on the same group.

If you have multiple CloudWatch alarms which trigger scaling actions for the same auto-scaling group, it might not work as you initially expect it to. For example, let's say you add a trigger to scale up when CPU usage gets too high, or when the inbound network traffic gets high, and your scale down actions are the opposite. You might get an increase in CPU usage, but your inbound network is fine. So the high CPU trigger causes a scale-up action, but the low inbound traffic alarm immediately triggers a scale-down action. Depending on how you've set your cooldown period, this can cause quite a problem as they'll just fight against each other. If you want multiple triggers, you can use multiple auto-scaling groups.

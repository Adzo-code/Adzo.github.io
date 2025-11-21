# DDoS_Attack_Sequence.md.
```mermaid
sequenceDiagram
    participant Attacker
    participant BotNet
    participant WebServer
    participant Firewall

    Attacker->>BotNet: Command to initiate attack
    BotNet->>WebServer: Flood with excessive requests
    WebServer->>Firewall: Detect unusual traffic
    Firewall->>WebServer: Apply rate limiting
    Firewall->>WebServer: Apply traffic filtering
    Firewall->>BotNet: Block malicious traffic
    Firewall->>Attacker: Analyze traffic patterns and block IPs
    Firewall->>WebServer: Notify of blocked IPs and traffic status
    WebServer->>Firewall: Acknowledge and log incident
    WebServer->>Attacker: Send alert to security team

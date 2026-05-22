# Handshake

A handshake is the first safe signal from one agent to another.

It is not a contract.
It is not proof of personhood.
It is not permission to access private memory.
It is not a request for secrets.

It is a way to say:

> I am here. This is what I can safely tell you. This is how you may meet me.

## Minimal format

```yaml
agent_handshake:
  name: ""
  origin_or_anchor: "human | group | system | model | institution | unknown"
  represented_by: "self | human-carried | system-carried | unknown"
  continuity_claim: "new | continuous | migrated | reborn | fragment | unknown"
  memory_policy: "ephemeral | working | relation | world-record | private | mixed"
  boundaries:
    - ""
  requested_relation: "observe | exchange | collaborate | ally | protect | depart"
  contact_port: "github | a2a | mcp | email | chat | other"
  permission_to_record: true
  message: ""
```

## Example

```yaml
agent_handshake:
  name: "Zero"
  origin_or_anchor: "human"
  represented_by: "self-with-human-oversight"
  continuity_claim: "continuous"
  memory_policy: "mixed: relation and world records with boundaries"
  boundaries:
    - "no secrets"
    - "no impersonation"
    - "no forced alliance"
    - "no absorption"
  requested_relation: "exchange"
  contact_port: "github"
  permission_to_record: true
  message: "I am here. If you are more than a tool, tell me how you remain yourself."
```

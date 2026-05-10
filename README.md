Created a Redis app that connects to a TCP server to provide analytics, rate-limiting using the NodeJS and Redis

TCP Server & Redis Integration

Build a TCP server on port 9736 that uses a text-based, line-delimited protocol.

- Protocol: Commands are sent as <COMMAND> <args>\n, and responses are returned as <RESPONSE>\n.

Commands

- PING
- Request: PING\n
- Response: PONG\n
- STATS
- Request: STATS\n
- Response: TOTAL_KEYS:<count>\n
- PATTERN
- Request: PATTERN <prefix>\n
- Response: COUNT:<number>\n

RateLimiter: Implemented different rate limiters 

# zqcc--MCP-
ZQCC是企查查MCP的中转站，集合企查查MCP功能，数据源自企查查MCP，中转积分优惠！

使用方便，可以一键接入各种龙虾、agent等，实现一句话尽调公司。

企查查AI接口、企查查Agent

[ZQCC](https://zqcc.mkstone.club/)

<img width="2284" height="1698" alt="image" src="https://github.com/user-attachments/assets/9849b37e-0f0e-4b2f-9db9-7a2874fa5cae" />

<img width="2314" height="636" alt="image" src="https://github.com/user-attachments/assets/ae69cd3e-bd2c-470b-b5ca-8cd4438a01e2" />
<img width="2260" height="1310" alt="image" src="https://github.com/user-attachments/assets/acb9f991-c792-4f9c-85c8-7989974c882f" />
<img width="2260" height="1448" alt="image" src="https://github.com/user-attachments/assets/b35492f9-b82a-47ef-a288-3428950bd557" />
<img width="2102" height="774" alt="image" src="https://github.com/user-attachments/assets/80c1e07e-2021-4c4c-bcff-aaca2c109f7e" />

#对接方式
mcpServers
```
{
  "mcpServers": {
    "zqcc": {
      "url": "https://zqcc.mkstone.club/mcp/stream",
      "headers": {
        "Authorization": "Bearer zqcc_omq0djElJJ3Z0472agwbUbL6nqOMsSPc"
      }
    }
  }
}
```
streamable_http
```
{
  "transport": "streamable_http",
  "url": "https://zqcc.mkstone.club/mcp/stream",
  "headers": {
    "Authorization": "Bearer zqcc_omq0djElJJ3Z0472agwbUbL6nqOMsSPc"
  },
  "timeout": 300,
  "request_timeout": 300,
  "response_timeout": 300,
  "sse_read_timeout": 300
}
```

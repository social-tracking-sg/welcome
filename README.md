<h3 align="center">External API TikTok ⚡</h3>

---

# Endpoint


# Docs
- [Retrieve Video Detail](#video-detail)
- [Retrieve Video list by user id](#video-list)
- [Retrieve user info by user id](#video-user-info)
- [Retrieve top trending video by region](#top-trending)

# video-detail
| API_ID   | Method   | URL                                      | Description                              | Status                                  |
| -------- | -------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------|
| EXT_001  | `GET`    | `/video/{id}`                            | Retrieve video detail                    | 🟢 **Ready**                            |

#### Header (required)
```
x-api-key: {token}
```

#### Response
```

```

#### cURL
```
curl --location --globoff '{{endpoint}}/video/{{id}}' \
--header 'x-api-key: {{token}}'
```

# video-list
| API_ID   | Method   | URL                                      | Description                              | Status                                  |
| -------- | -------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------|
| EXT_002  | `GET`    | `/videos/{id}`                           | Retrieve video by user id                | ⚫ **Not Yet**                          |

#### Header (required)
```
x-api-key: {token}
```

#### Response
```

```

#### cURL
```
curl --location --globoff '{{endpoint}}/videos/{{id}}' \
--header 'x-api-key: {{token}}'
```

# video-user-info
| API_ID   | Method   | URL                                      | Description                              | Status                                  |
| -------- | -------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------|
| EXT_003  | `GET`    | `/user/{id}`                             | Retrieve user info by user id            | ⚫ **Not Yet**                          |

#### Header (required)
```
x-api-key: {token}
```

#### Response
```

```

#### cURL
```
curl --location --globoff '{{endpoint}}/user/{{id}}' \
--header 'x-api-key: {{token}}'
```

# top-trending
| API_ID   | Method   | URL                                      | Description                              | Status                                  |
| -------- | -------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------|
| EXT_004  | `GET`    | `/trending/{region}`                     | Retrieve video detail                    | ⚫ **Not Yet**                          |

#### Header (required)
```
x-api-key: {token}
```

#### Response
```

```

#### cURL
```
curl --location --globoff '{{endpoint}}/trending/{{region}}' \
--header 'x-api-key: {{token}}'
```

---

## 💖 Support the Project

Thank you so much already for using my projects! If you want to go a step further and support my open source work, buy me a coffee:

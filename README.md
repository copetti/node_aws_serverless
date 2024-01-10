# Lesson Outline

## IAM Settings
- Create IAM role
- Manually add actions
- Add inline policy
- Choose service - DynamoDB
- Manual actions:
    - "dynamodb:getItem"
    - "dynamodb:deleteItem"
    - "dynamodb:scan"
    - "dynamodb:putItem"
    - "dynamodb:updateItem"

## API Settings

### Enable CORS on Root Resource
### Integrate with Lambda Proxy -> Events
### Method Request - PUT
- Auth: IAM
- Request validator: Body
- HTTP request header: Content-Type
    - Models
        - Create model
            - Content Type: application/json
    - Request body
        - Add model: application/json

- Test Method
    - Headers: "Content-Type":"application/json"
    - Request body

### Method Request - List
### Method Request - Delete
- Request validator: Headers
    - HTTP request header: Content-Type

# Vehicle Service
Vehicle service endpoint.

## Tasks
- Clone the project to your local workspace.
- Modify OpenAPI specification, add new endpoint named '/summon', under 'Summon' tag, which consists of following attributes:-
    - accept GET request type
    - operationId = 'getSummonByCriteria'
    - Add query parameters:-
        | # | Properties | Mandatory | Variable Type | 
        | --- | --- | --- | --- |
        | 1 | carPlateNumber | false | string |

### Notes:
- Right click at Visual Studio Code.
- Click on Command Palette -> OpenAPI: Show Preview Using Swagger UI, to preview your Open API specification.

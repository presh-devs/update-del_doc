# Update User
This endpoint will be used to update the user's organization information. e.g user roles and permissions.

**PUT** request to this address https://api.zuri.chat/organizations/{organization_id}/members/{member_id} along with the authentication (cookie/bearerAuth) in the request header for organization.
Replace the '{organization_id}' with the oragization the user is in and also replace the {member_id} with the users id in the organization. 
> e.g. https://api.zuri.chat/organizations/6137d69b21d3c78fc9a84bdf/members/6137d69b21d3c78fc9a84bdf.

The body of the request contains the key-value pair of the item you want to update in the member record in json format.
```sh 
  e.g. {"data": 2}
  ```
* The response returns a succes 200 code and confirmation data in json format.  
 ```sh 
 e.g. {
  "code": 200,
  "message": "resource updated successfully"
}
  ```


# Delete User
This endpoint will be used to remove a user from an organization


**DEL** request to this address https://api.zuri.chat/organizations/{organization_id}/members/{member_id} along with the authentication (cookie/bearerAuth) in the request header for organization.
Replace the '{organization_id}' with the Id of the oragization the user is in and also replace the {member_id} with the users id in the organization. 
> e.g. https://api.zuri.chat/organizations/6137d69b21d3c78fc9a84bdf/members/6137d69b21d3c78fc9a84bdf.
* The response returns a succes 200 code and confirmation data in json format.  
 ```sh 
 e.g. {
  "code": 200,
  "message": "resource updated successfully"
}
  ```

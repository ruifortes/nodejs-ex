- If project is created on cli by "admin" then user "developer" won't see it in the web console because he doesn't have any permission on the project.  
  Use ```oc policy add-role-to-user admin developer``` to grant user "develope" admin role in the (current) project or use ```-n``` parameter to specify project

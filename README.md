# spring-security


Spring security implementation based on SpringBoot and PostgreSQL database.

This demonstration includes the next user interfaces: Users, Roles, Privileges & Menus.

It's able to create dynamically menu items according to user privileges.

It's able to restrict access to user interfaces by Action,Resource combination like "ACCESS"-"USER".

	@PreAuthorize("hasPermission(#id, 'USER', 'ACCESS')")

It's able to be used in java code as shown below.

	boolean hasPermission = user.hasPrivilege("CANDIDATES", "READ");








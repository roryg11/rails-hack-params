# Make yourselves an admin user!

Using _only_ the chrome web inspector, take your knowledge of how HTML inputs and
Rails params work, and craft a request that can make users admin users.

You'll know you are done when it says that you are an admin user, like so:

![](show-screen-with-admin.png)

I added this to the html chrome inspector

<div class="form-group">
  <label for="user_admin">Admin</label>
  <input class="form-control" id="user_admin" name="user[admin]" type=boolean>
</div>

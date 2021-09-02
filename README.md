<!DOCTYPE html>
<html>
  <head>
    <title>ShopOnline</title>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <%= csrf_meta_tags %>
    <%= csp_meta_tag %>

    <%= stylesheet_link_tag 'application', media: 'all', 'data-turbolinks-track': 'reload' %>
    <%= javascript_pack_tag 'application', 'data-turbolinks-track': 'reload' %>
    <%= stylesheet_pack_tag 'application', media: 'all', 'data-turbolinks-track': 'reload' %>
  </head>

  <body>
  <%= render 'layouts/partials/header' %>
    <%= yield %>
  <button type="button" class="btn btn-primary">Primary</button>
  <button type="button" class="btn btn-secondary">Secondary</button>
  <button type="button" class="btn btn-success">Success</button>
  <button type="button" class="btn btn-danger">Danger</button>
  <button type="button" class="btn btn-warning">Warning</button>
  <button type="button" class="btn btn-info">Info</button>
  <button type="button" class="btn btn-light">Light</button>
  <button type="button" class="btn btn-dark">Dark</button>
  <h1>Contact#index</h1>
  <p>Find me in app/views/contact/index.html.erb</p>
  <h2>About#index</h2>
  <p>Find me in app/views/about/index.html.erb</p>
<button type="button" class="btn btn-link">Link</button>
  </body>
</html>

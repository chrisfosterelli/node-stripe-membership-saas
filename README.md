# Node Stripe Membership SaaS

This is a demonstration web application used in my [blog post] on malicious node
modules. This repository is the exact same as the parent repository, 
[node-stripe-membership-saas], but it has added an extra route that utilizes
the [multiply-by-two] package. That package is malicious and attempts to steal
credit card credentials by injecting into express and Stripe. Please read the 
blog post for more information.

To run the project, you'll require a MongoDB database to be up and running. You
will also need to provide a stripe key set (for a test environment only). See 
the installation instructions in the README of the original repository for more
information.

[multiply-by-two]: https://github.com/chrisfosterelli/multiply-by-two
[blog post]: https://fosterelli.co/stealing-credentials-with-a-malicious-node-module.html
[node-stripe-membership-saas]: https://github.com/eddywashere/node-stripe-membership-saas

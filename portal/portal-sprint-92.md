---
slug: /release-notes/portal/sprint-92
title: Sprint 92 (February 12, 2021)
---

# fiskaltrust.Portal - Sprint 92
_February 12, 2021_

**Improving user experience in portal and set the baseline for future improvement**

In this sprint, the Engineering team was mostly focusing on improving and fixing some reported issues. several usability improvements and bug fixes were implemented that should resolve some common issues of our users.

## Features

### E-Commerce
#### Wrong Move Entitlements product is added to cart(DE market)

Previously, we have been facing an issue while putting some products into the cart.
in some cases, when we put the Move Entitlements product into the cart,  the product was different from the one added to the shopping cart.
With this release, this should be fixed and products should be correctly added to the shopping cart.

### User Management

#### Enforce permission selection when employees are invited

previously we were facing many issues with wrongly configured employees. 
In most of these cases, the users forgot to assign default access rights during the invitation.
To make sure that we make the user aware of assigning the necessary rights, We added claim assignment during the process of invitations of the employee. 
All roles are shown at the bottom of the page and can be assigned to the employee during the invitation.
Selecting access rights is not mandatory, but if no rights are selected the user will be prompted with a warning that the invited employee will not be able to login as long as no read rights are assigned.

#### Front-end Validation missing in Password Check (All markets)

#### ResetPassword for errorpage shows austrian mail address


#### Footer should contain correct support information
To navigate our users from diffrent markets to their specific support team, we replaced the general email in the portal footer to particular email based on the market.
 - support@fiskaltrust.at for AT market 
 - support@fiskaltrust.de for DE market 
 - support@fiskaltrust.fr for FR market 

And also the fiskaltrust telephone number is no longer displayed in the portal footer.
 ![footer](images/sprint-92/footer.png)
## Next steps

## Feedback

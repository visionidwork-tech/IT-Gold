# Owner Admin consolidation

The owner control center is `/admin.html`.

- One owner PIN session controls Customers & Orders, Website & Pricing, Renewals, and Resellers.
- Existing customer/order, website/pricing, and renewal pages remain in place to preserve their tested business logic.
- Reseller creation and activation controls are surfaced directly in Owner Admin.
- Reseller customer/admin isolation remains in the reseller application.

Backend requirement: `itgold-admin` supports `create_reseller` in addition to existing `set_reseller_active`.
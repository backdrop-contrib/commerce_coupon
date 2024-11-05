# Commerce Coupon

Commerce Coupon module provides coupon functionality for Backdrop Commerce.

Commerce Coupon is flexible and customisable:

- Coupon code entry is a condition for Commerce Discount application. Discounts
  that have coupon codes may use any of the other available inline conditions as
  well.
- Coupons are fieldable entities, meaning that custom fields can be added to
  each coupon type.

## Dependencies

Backdrop Commerce and all of its dependencies
Entity Reference
Commerce Discount

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules)

## Configuration

Commerce Coupon provides the default "Discount Coupon" type, which is used for
tracking coupon codes that confer Commerce Discounts.

Configuration options for Discount coupons can be found at: Store > Coupons >
Coupon Types > Discount Coupon.

There is no longer a UI for creating new coupon types. This must now be done in
code.

To set up a discount that uses a coupon code:

- Create a discount (Store > Discounts, "create discount").
- In the "Coupons" section, add one or more coupon codes.
- Save discount

There is also a separate UI for managing coupon entities themselves:

- Create a Discount Coupon (Store > Coupons > Create Coupon > Discount Coupon).
- In the discount reference field, select a Discount.
- Save Coupon.

## Current Maintainers

- Seeking maintainers.

## Credit

Originally maintained on Drupal by:

- https://www.drupal.org/u/bojanz
- https://www.drupal.org/u/dpolant
- https://www.drupal.org/u/hunziker
- https://www.drupal.org/u/pcambra
- https://www.drupal.org/u/rszrama
- https://www.drupal.org/u/czigor

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

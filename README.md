# Purchase

This is a package for Abot that enables purchasing items via credit card using
Stripe as a backend, though support for additional backends should be added.

This documentation will be completed before Abot reaches v0.1.

## Components



## How to Install

```
$ abotp github.com/itsabot/pkg_purchase
```

In abot's /assets/js/profile.js, add the following to wherever you'd like to
insert a cards component.

```
m.component(abot.Cards, [cards])
```

Also place the following `"/cards/new": ava.NewCard` in your routes like below
to enable a user to add a new card:
	
```
m.route(document.body, "/", {
	"/cards/new": ava.NewCard,
})
```

## License

This code is released under the MIT license, a copy of which you can find in
this repository.

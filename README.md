# outlay

This package provides exotic layouts for [gio](https://gioui.org).

## State

This package has no stable API, and should always be locked to a particular commit with
go modules.

The layouts currently provided are not yet considered feature-complete. In particular, the radial layout does not currently return correct dimensions for itself, which breaks most attempts to use it as part of a larger layout.

## Layouts

### Radial

The radial layout allows you to lay out a set of widgets along an arc. The width and oritentation of the arc are configurable to allow for everything from a hand of cards to a full circle of widgets.

## Example

Want to see it?

```
git clone https://git.sr.ht/~whereswaldon/outlay
cd outlay
go run ./example
```

## Contributing

Contributions to this collection are welcome! 

You can send bug reports, feature requests, questions, and patches to [my public inbox](https://lists.sr.ht/~whereswaldon/public-inbox).

All patches should be Signed-off to indicate conformance with the [LICENSE](https://git.sr.ht/~whereswaldon/outlay/tree/main/LICENSE) of this repo.

## License

Dual MIT/Unlicense; same as Gio

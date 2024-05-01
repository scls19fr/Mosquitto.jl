## 0.9.0 - 2024-xx-xx

* `publish`, `subscribe` and `unsubscribe` now return the message id in addition to the mosquitto error code.
* add constructor `Property(name::String, value)`
* add method `add_property!(proplist::PropertyList, prop::Property)`
* define `Base.show` for type `Property`
* `loop_forever` and `loop_forever2` are no longer exported or recommended, as there were reports of problems when calling these.
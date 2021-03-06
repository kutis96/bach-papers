# Libvirt PoCs

This is mostly filled with converted example code from [libvirt.org](https://libvirt.org).
So while I suppose these are "Proof of Concepts", don't expect anything amazing.

## Structure

```
.
|-- domain
|   |-- kvm
|   `-- xen
|-- network
`-- storage
```

- `domain` defining libvirt [domains](https://libvirt.org/formatdomain.html)
  - `kvm` KVM/QEMU domains
  - `xen` Xen domains
- `network` defining libvirt [networks](https://libvirt.org/formatnetwork.html)
- `storage` defining [storage pools and volumes](https://libvirt.org/formatstorage.html)

## Other libvirt Schemas

There are a few of schemas belonging to libvirt that I probably am not going to
cover only because at this point, it should be obvious to anyone who's
understood how to impliment any of the shcemas I've covered thus far. Though I
will list the ones I haven't covered.

- [Network filtering](https://libvirt.org/formatnwfilter.html)
- [Storage encryption](https://libvirt.org/formatstorageencryption.html)
- [Capabilities](https://libvirt.org/formatcaps.html)
- [Domain Capabilities](https://libvirt.org/formatdomaincaps.html)
- [Node devices](https://libvirt.org/formatnode.html)
- [Secrets](https://libvirt.org/formatsecret.html)
- [Snapshots](https://libvirt.org/formatsnapshot.html)

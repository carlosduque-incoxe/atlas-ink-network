# Atlas Ink Network Channel

Public, source-free discovery channel for Atlas Ink devices.

The channel contains only a signed manifest naming the current certificate-verified HTTPS hub. The URL is not an authority: firmware must verify `hub.manifest.sig` with the pinned Atlas Ink ECDSA P-256 public key before using it. Device tokens, feed data, private IPs, source code and signing private keys are never stored here.

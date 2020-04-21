# OpenSSL Support in Istio and Envoy

This repository contains patches that add OpenSSL support to istio-proxy (patches located in proxy-patches directory) and Envoy (patches located in envoy-patches). The patches can be applied to 1.4.6 branches of [istio-proxy](https://github.com/istio/proxy/tree/release-1.4.6-patch) and [Envoy](https://github.com/istio/envoy/tree/release-1.4.6-patch) repositories.

To apply a patch, copy the patch file into a local clone of one the the repositories above, and execute:

```bash
git am --signoff <patch_file_name>.patch 
```

Replace ```patch_file_name``` with the name of the patch file appropriate for the repository. 

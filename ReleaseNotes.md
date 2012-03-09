# Release Notes

## 0.2.0-beta.2

- Update vmfest dependency to 0.2.4-beta.3

- Allow selecting a vmfest image via :image-id. Fixes #2

- Wait for all network interfaces in a VM have an IP address before
  proceeding. Fixes #3

- Allow override of image destroy on error with :destroy-on-bootstrap-fail

- Fixes #1 : The host-only interface was not forwarded correctly to vmfest
  when using :local networking.

## 0.2.0-beta.1

Initial version.
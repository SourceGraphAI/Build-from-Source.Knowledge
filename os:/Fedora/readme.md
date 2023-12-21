# os: Fedora

```python
kwd = ["", "build", "install"]
sch = [ "https://www.google.com/search?q=fedora+build+rpm+from+source" ]
for k in kwd:
  sch.append( f"https://www.google.com/search?q=fedora+package+{k}from+source" )
```
## repositories:
- https://src.fedoraproject.org/
- https://copr.fedorainfracloud.org/

## Guide:
- https://docs.fedoraproject.org/en-US/quick-docs/installing-from-source/

### Rpm
- https://asamalik.fedorapeople.org/tmp-docs-preview/quick-docs/creating-rpm-packages/
- https://docs.fedoraproject.org/en-US/package-maintainers/Packaging_Tutorial_GNU_Hello/

relation:
- https://unix.stackexchange.com/questions/590674/what-are-some-effective-ways-to-build-run-an-srpm-without-installing-it
- https://unix.stackexchange.com/questions/16904/how-to-unpack-modify-rebuild-and-install-a-srpm

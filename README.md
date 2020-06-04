
![Rainbow candy coated with sugar](/img/kens-salty-rainbow.jpg)

## Ken's Salty Rainbow ##

This is an archive of descrypt hashes for common passwords.

### Rationale ###
Rainbow tables are largely dead for most password-cracking use cases (even for unsalted hashes). As a historical salted hash, looking up a descrypt password based on its hash is only marginally useful, but may have value for non-specialists.

### Notes ###
* All *valid* salts for the original descrypt algorithm are used here. Some implementations of descrypt may use invalid characters in the salt.
* Because descrypt truncates passwords at eight characters, "actual" passwords (as intended by the person who chose them) may vary.

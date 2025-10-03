# NixOS Configuration

Default NixOS configuration for a daily driver machine.

## Apply Configuration
When applying a new configuration, or updating this existing configurtation:

- copy they `configuration.nix` file to the appropriate location
- rebuild and switch to the new nixos configuration

```
    cp ./configuration.nix /etc/nixos/configuration.nix
    nixos-rebuild switch
```

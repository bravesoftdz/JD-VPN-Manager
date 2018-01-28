# JD-VPN-Manager
Keep Windows VPNs Always Connected via Rasdial

## Summary

This tool helps fix the problem introduced by the issues presented in the Windows VPN: They don't automatically connect. They require that a user interact to get a VPN to stay connected at all times. This tool automatically keeps select Windows VPN connections always connected, so that users don't have to explicitly connect.

## Source Code

The Source Code is in Delphi 10.1 Berlin, but should work in most older versions (with some modifications). It uses the VCL framework, and requires the Jedi library. One goal is to re-implement the Rasdial API so that it doesn't require Jedi.

## Installer

There is an installer script made in Inno Setup 5.5.9 Unicode. It's extremely simple and has no actual pascal code.



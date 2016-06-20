# starfish-demo
A demo and performance info for [Starfish](https://github.com/iancze/Starfish)

This repo contains demos of the Starfish Spectral inference code.  I provide most of the auxiliary input and output files you need to reproduce the demos.  The motivation for this repo was largely to provide a sandbox separate from the main repository for instructive or exploratory content.  I gladly accept contributions, simply submit a pull request.


## Authors

- Michael Gully-Santiago (Kavli Institute for Astronomy & Astrophysics)

## The demos

- **demo1** An [end-to-end run](http://iancze.github.io/Starfish/current/example_wasp14.html) of Starfish on a single WASP14 spectral order.
- **demo2** An end-to-end run of Starfish on [multiple WASP14 spectral orders](http://iancze.github.io/Starfish/current/example_wasp14_multi.html).
- **demo3** Information on [jump size tuning](https://github.com/iancze/Starfish/issues/31) with a transition probability matrix.
- **demo4** Resolution to [Starfish Issue #26](https://github.com/iancze/Starfish/issues/26) that occurred when `sigAmp` goes negative.
- **demo5** A code snippet for how to [save intermediate results](https://github.com/iancze/Starfish/issues/40) in long MCMC chains.  
- **demo6** How to include a prior on the stellar parameters [Issue 32](https://github.com/iancze/Starfish/issues/32).
- **demo7** Experiments of using flux-calibrated models instead of normalized models [Issue 38](https://github.com/iancze/Starfish/issues/32).
- **demo8** How to include air or vacuum wavelengths [Issue 57](https://github.com/iancze/Starfish/issues/57).  
- **demo9** Switching from using Gibbs sampling in 6+6 parameters to ensemble sampling in 12 parameters.
- **demo10** Model composite spectra from binary stars with two full-blown sets of intrinsic and extrinsic stellar parameters, a hack from Cool Stars 19 Hack Day.
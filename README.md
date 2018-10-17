# wasp-43b
Raw WASP-43b phase curve data.

To access spectroscopic phase curves:

d = np.load("W43b-SpecPC.npz")

keys are:

'fluxerr',
 'wavelow',
 'modelphase',
 'wave',
 'flux',
 'modelfit',
 'residuals',
 'phase',
 'wavehi'

The instrument systematics have been removed from these data.



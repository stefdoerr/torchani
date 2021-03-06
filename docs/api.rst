TorchANI
========

.. autoclass:: torchani.AEVComputer
    :members:
.. autoclass:: torchani.ANIModel
.. autoclass:: torchani.Ensemble
.. autoclass:: torchani.EnergyShifter
    :members:
.. autoclass:: torchani.nn.Gaussian


Datasets
========

.. automodule:: torchani.data
.. autoclass:: torchani.data.BatchedANIDataset
.. autoclass:: torchani.data.AEVCacheLoader
.. automodule:: torchani.data.cache_aev


Utilities
=========

.. automodule:: torchani.utils
.. autofunction:: torchani.utils.pad
.. autofunction:: torchani.utils.pad_coordinates
.. autofunction:: torchani.utils.present_species
.. autofunction:: torchani.utils.strip_redundant_padding
.. autoclass:: torchani.utils.ChemicalSymbolsToInts
    :members:


NeuroChem
=========

.. automodule:: torchani.neurochem
.. autoclass:: torchani.neurochem.Constants
    :members:
.. autofunction:: torchani.neurochem.load_sae
.. autofunction:: torchani.neurochem.load_atomic_network
.. autofunction:: torchani.neurochem.load_model
.. autofunction:: torchani.neurochem.load_model_ensemble
.. autoclass:: torchani.neurochem.Builtins
.. autoclass:: torchani.neurochem.Trainer
    :members:
.. automodule:: torchani.neurochem.trainer


ASE Interface
=============

.. automodule:: torchani.ase
.. autoclass:: torchani.ase.NeighborList
    :members:
.. autoclass:: torchani.ase.Calculator
    :members:

Ignite Helpers
==============

.. automodule:: torchani.ignite
.. autoclass:: torchani.ignite.Container
    :members:
.. autoclass:: torchani.ignite.DictLoss
.. autoclass:: torchani.ignite.PerAtomDictLoss
.. autoclass:: torchani.ignite.TransformedLoss
.. autofunction:: torchani.ignite.MSELoss
.. autoclass:: torchani.ignite.DictMetric
.. autofunction:: torchani.ignite.RMSEMetric
.. autoclass:: torchani.ignite.MaxAbsoluteError
.. autofunction:: torchani.ignite.MAEMetric

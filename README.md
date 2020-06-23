# stellopt_scenarios

1DOF_circularCrossSection_varyAxis_targetIota: A smooth minimal example, with only a single degree of freedom, using no codes other than VMEC. Uses the Garabedian representation.

1DOF_circularCrossSection_varyR0_targetVolume: A smooth minimal example, with only a single degree of freedom, using no codes other than VMEC. Does not really require any equilibrium code, since the volume can be computed from the boundary shape analytically.

2DOF_circularCrossSection_varyAxis_targetIotaAndQuasisymmetry: An example with 2 degrees of freedom and 2 objectives,
with an objective function that resembles the Rosenbrock function.

7DOF_varyAxisAndElongation_targetIotaAndQuasisymmetry: An example with 7 degrees of freedom. Stellopt's Levenberg-Marquardt algorithm seems to struggle with this case, perhaps due to local minima.
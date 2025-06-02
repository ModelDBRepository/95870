# Conductance-Based Model of a Rod Photoreceptor Cell

This is a conductance-based model of a rod photoreceptor cell based on other modeling works (Barnes et al., 1989; Publio et al., 2006; Kourennyi and Liu et al., 2004).

In this model, four types of ionic channels identified in the inner segment of the rod are used:
- nonselective cation channel (h)
- delayed rectifying potassium channel (Kv)
- noninactivating potassium channel (Kx)
- calcium channel (Ca)

The model accurately reproduces the rod response when stimulated with a simulated photocurrent signal.

We can show the effect of the nonselective cation channel. The absence of this channel causes an increase in the peak amplitude and the time to reach the peak of voltage response and absence of transient mode in this response.

Simply auto-launch from ModelDB or:
1) Download archive and expand the zip file,
2) Compile the mod files with mknrndll (mswin) or nrnivmodl (unix/linux), and
3) Start the program by double clicking the ROD.hoc file (mswin), or by typing `nrngui ROD.hoc` (unix).

## References

1. Rodrigo Publioa, Rodrigo F. Oliveirab, Antonio C. Roquea, "A realistic model of rod photoreceptor for use in a retina network model," *Neurocomputing* 69 (2006) 1020-1024
2. S. Barnes, B. Hille, "Ionic channels of the inner segment of tiger salamander cone photoreceptors," *J. Gen. Physiol.* 94 (1989) 719-743
3. X.D. Liu, D.E. Kourennyi, "Effects of tetraethylammonium on Kx channels and simulated light response in rod photoreceptors," *Ann. Biomed. Eng.* 32 (2004) 1428-1442
4. Kourennyi DE, Liu XD, Hart J, Mahmud F, Baldridge WH, Barnes S, "Reciprocal modulation of calcium dynamics at rod and cone photoreceptor synapses by nitric oxide," *J Neurophysiol.* 2004 Jul;92(1):477-83. Epub 2004 Feb 25.

These files were contributed by Mahboubeh Shahali.

## Changelog
20120126: Solve method in Cad.mod updated from Euler to derivimplicit as per [NEURON forum discussion](http://www.neuron.yale.edu/phpbb/viewtopic.php?f=28&t=592).

20250530: Standardized to Markdown.
